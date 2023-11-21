# GWAS_PWAS_Sia
##GWAS & PWAS notebook##

✔✔✔✔#Step_1..........................................................................................................
Downloading & installation toools 

- [Example 1](https://www.example.com)



Say what the step will be

    Give the example

And repeat

    until finished

1. Plink 

PLINK1.9 : https://www.cog-genomics.org/plink/
PLINK2 : https://www.cog-genomics.org/plink/2.0/

cd ~
mkdir tools
cd tools
mkdir bin
mkdir plink
mkdir plink2

cd plink2
wget https://s3.amazonaws.com/plink2-assets/plink2_linux_x86_64_20211011.zip
unzip plink2_linux_x86_64_20211011.zip


cd ~
ln -s ~/tools/plink2/plink2 ~/tools/bin/plink2
ln -s ~/tools/plink/plink ~/tools/bin/plink

export PATH=$PATH:~/tools/bin/

echo "export PATH=$PATH:~/tools/bin/" >> ~/.bashrc

plink -h


