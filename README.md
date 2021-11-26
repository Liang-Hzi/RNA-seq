# RNA-seq
>wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh   （install Miniconda3 Linux 64-bit）
until showing Thank you for installing Miniconda3! (location: /home/xxx/miniconda3)
>cd /home/xxx/miniconda3/bin
>ll (you will find activate*)
>chmod 777 activate
>. ./activate (now conda is activated, then "base"showing before your name)
>conda config --add channels defaults
>conda config --add channels bioconda
>conda config --add channels conda-forge
>conda install nextflow (lasting)
>conda install nf-core (lasting)
>nf-core download nf-core/rnaseq (select 3.4, singularity,no,tar.gz)
