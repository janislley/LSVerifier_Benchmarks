# LSVerifier Benchmarks

This most recent repository contains the vulnerability analysis results performed in some C open-source software projects.

All open-source software codes are distributed under the Open-source license (GNU GPL, Apache, and MIT). 

These programs have been selected due to their high importance in the open-source community and the large size with a significant open-source third-party library used.

## Verification process

~~~
$ cd <Software>
$ lsverifier -r -v -f -e "--unwind 1 --no-unwinding-assertions" -i dep.txt
~~~

## Software versions

| Software      | Version   | 
| :------------ |:---------:| 
| VIM           | 8.2.3908  |   
| RUFUS         | 3.17      |  
| OpenSSH       | 8.8       |     
| Wireshark     | 3.6       |    
| Putty         | 0.76      |  

## References

* VIM: https://github.com/vim/vim
* RUFUS: https://github.com/pbatard/rufus
* OpenSSH: https://github.com/openssh/openssh-portable
* Wireshark: https://github.com/wireshark/wireshark
* Putty: https://github.com/github/putty


