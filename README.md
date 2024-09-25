# faiss_exp

sudo apt update

git clone https://github.com/facebookresearch/faiss.git

sudo apt install build-essential libssl-dev -y

wget https://github.com/Kitware/CMake/releases/download/v3.27.5/cmake-3.27.5.tar.gz

tar -zxvf cmake-3.27.5.tar.gz

cd ./cmake-3.27.5

./bootstrap 

make -j32

sudo make install




