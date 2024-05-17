# STACKS
Pipeline para realizar control de calidad de reads, recortar la longitud a un tamaño específicos, construccion de RAD locus, llamado de SNP's y filtrado de SNP's

# Instalar con conda
conda install bioconda::stacks

conda install bioconda/label/cf201901::stacks


# Si se compila la instalación compilando, se debe instalar c++ y la librerìa z-lib en linux
 https://github.com/vcftools/vcftools.
 El manual de vcftools se encuentra aquí: https://vcftools.sourceforge.net/man_latest.html

sudo make install
sudo apt install zlib1g-dev
