# gossamer
docker container for [gossamer bioinformatics suite](https://github.com/data61/gossamer)

A singularity image can be create from the definition file.

What you only need to do is to change the path to gossamer to your own local path.

%files  
**path/to/gossamer** /home/gossamer

After given the right path, you can run the command below in a linux system with sudo.
`sudo singularity build example.sif Deffile`


