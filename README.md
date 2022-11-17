create ubuntu intance 
add security group NFS port(2049)
connect the intance by ssh 
apt update 
apt install nfs* -y or (nfs_comman)
mkdir /efs
go to amazon efs service 
create filesystem configer all the step 
select your file system 
selete attach 
go to mount via ip 
copy nfs cline url 
go to mobaectrem
past the nfs clint url in mobaectrem for ex (sudo mount -t nfs4 -o nfsvers=4.1,rsize=1048576,wsize=1048576,hard,timeo=600,retrans=2,noresvport 172.31.13.7:/ /efs)
