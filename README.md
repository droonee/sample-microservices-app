# sample-microservices-app

How to run the sample application
1. Launch an Ubuntu AWS EC2 instance with inbound & outbound traffic wide open on all ports
2. Get the code on the EC2 instance `git clone https://github.com/droonee/sample-microservices-app.git`
3. Get into the directory with `cd sample-microservices-app`
4. Check that Python 3.X is installed on your machine `python3 -V` - should be Python 3.10.X
5. Need to update the EC2 instance before installing Python packages
    1. `sudo apt update`
    2. `apt list --upgradable`
    3. Install pip `sudo apt install pythong3-pip`
6. Check that pip is installed `pip -V`
7. Install the dependencies `pip install -r requirements.txt`
8. Run the sample microservices app `python3 run.py`
