# Dual channel FSKCW (QRSS) using Siglent SDG 1032X

## Configure
* Connect generator to RPi GPIO12
* copy config.py.dist to config.py and change the callsign / text and IP address of the signal generator.

* Configure frequencies in main.py (TODO: move to config.py).

* Create Python virtual environment and install required packages.

        python3 -m venv venv
        source venv/bin/activate
        pip -r install requirements.txt

* Run the script

        python3 main.py

