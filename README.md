# clk-1
little kernel port for HD2/LEO

mkdir clk
git clone -b BlackCLK_ex https://github.com/zeusk/clk blackclk
wget http://www.codesourcery.com/sgpp/lite/arm/portal/package5353/public/arm-none-eabi/arm-2009q3-68-arm-none-eabi-i686-pc-linux-gnu.tar.bz2
tar xvfj arm-2009q3-68-arm-none-eabi-i686-pc-linux-gnu.tar.bz2
PATH=/home/thinhnguyen/clk/arm-2009q3/bin:$PATH TOOLCHAIN_PREFIX=arm-none-eabi- PROJECT=htcleo make EMMC_BOOT=1

change name of host by yourself
