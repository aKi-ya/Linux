# Linux

change permission

a  all, r  read, w  write, x  execute
```
$chmod -R a+rwx /direcory
```
check permission
```
$ls -l
```
check internal, external mounted storage
````
lsblk -f
````
copy files across server 
```
scp file_to_transfer akshay@10.121.1.2:destination_folder
```

change GPU
````
export CUDA_VISIBLE_DEVICES=3
````
````
python test.py
````
