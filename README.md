# dataset
Open RadioML Synthetic Benchmark Dataset

#############

https://kb.ettus.com/Building_and_Installing_the_USRP_Open-Source_Toolchain_(UHD_and_GNU_Radio)_on_Linux#Update_and_Install_dependencies

sudo apt-get -y install git swig cmake doxygen build-essential libboost-all-dev libtool libusb-1.0-0 libusb-1.0-0-dev libudev-dev libncurses5-dev libfftw3-bin libfftw3-dev libfftw3-doc libcppunit-1.13-0v5 libcppunit-dev libcppunit-doc ncurses-bin cpufrequtils python-numpy python-numpy-doc python-numpy-dbg python-scipy python-docutils qt4-bin-dbg qt4-default qt4-doc libqt4-dev libqt4-dev-bin python-qt4 python-qt4-dbg python-qt4-dev python-qt4-doc python-qt4-doc libqwt6abi1 libfftw3-bin libfftw3-dev libfftw3-doc ncurses-bin libncurses5 libncurses5-dev libncurses5-dbg libfontconfig1-dev libxrender-dev libpulse-dev swig g++ automake autoconf libtool python-dev libfftw3-dev libcppunit-dev libboost-all-dev libusb-dev libusb-1.0-0-dev fort77 libsdl1.2-dev python-wxgtk3.0 git-core libqt4-dev python-numpy ccache python-opengl libgsl-dev python-cheetah python-mako python-lxml doxygen qt4-default qt4-dev-tools libusb-1.0-0-dev libqwt5-qt4-dev libqwtplot3d-qt4-dev pyqt4-dev-tools python-qwt5-qt4 cmake git-core wget libxi-dev gtk2-engines-pixbuf r-base-dev python-tk liborc-0.4-0 liborc-0.4-dev libasound2-dev python-gtk2 libzmq-dev libzmq1 python-requests python-sphinx libcomedi-dev python-zmq python-setuptools
#############

sudo apt install gnuradio

#############

~/.bashrc

PYTHONPATH=$PYTHONPATH:/path/to/gnuradio/lib/python2.7/dist-packages
export PYTHONPATH

LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/path/to/gnuradio/lib
export LD_LIBRARY_PATH

PATH=$PATH:/path/to/gnuradio/bin
export PATH
#############

#############
git clone git://github.com/pybombs/pybombs.git
cd ~/pybombs
python setup.py build
#############

gr-mediatools
sudo apt-get install libavcodec-dev libavformat-dev

https://github.com/osh/gr-mediatools

sudo mkdir build

cd build

sudo cmake ..

sudo make

sudo make install

sudo ldconfig

###########
gr-mapper

sudo git clone https://github.com/gr-vt/gr-mapper.git

cd gr-mapper

sudo mkdir build

cd build

sudo cmake ..

sudo make

sudo make install

sudo ldconfig
###########

sudo docker cp trusting_mahavira:/root/dataset/RML2016.10a_dict.pkl .



