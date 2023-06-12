# WatchDog

## Database.

```bash
sudo apt install postgresql
sudo apt-get install bluetooth libbluetooth-dev
sudo -i -u postgres
psql
\password

```

## Set up & Installation.

### 1 .Clone/Fork the git repo and create an environment 
                    
**Windows**
          
```bash
git clone https://github.com/WeiHanWong/779c708ac0843f43a54f0695e3271fdc.git
cd 779c708ac0843f43a54f0695e3271fdc
py -3 -m venv venv

```
          
**macOS/Linux**
          
```bash
git clone https://github.com/WeiHanWong/779c708ac0843f43a54f0695e3271fdc.git
cd 779c708ac0843f43a54f0695e3271fdc
python3 -m venv venv

```

### 2 .Activate the environment
          
**Windows** 

```venv\Scripts\activate```
          
**macOS/Linux**

```. venv/bin/activate```
or
```source venv/bin/activate```

### 3 .Install the requirements

Applies for windows/macOS/Linux

```
pip install -r requirements.txt
```

### 4. Run the application 

```
flask run
```
### 5. Login 

**Admin Credentials**

Username

```will```

Password

```password```
