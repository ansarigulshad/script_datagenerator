# How to use data generator script

#### 1. Download script
```
yum clean all
yum install git -y

cd /var/tmp/
git clone https://github.com/ansarigulshad/script_datagenerator.git
cd script_datagenerator
chmod +x *.sh
```

#### 2. Execute script
```
sh data_generator.sh
```

#### 3. Verify _employee_data.csv contents
```
head -50 employee_data.csv
```
