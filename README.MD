### Notes

Download the repo
```bash 
git clone https://github.com/JKoveDev/semantic-kernel-demo.git

cd semantic-kernel-demo
```

Install python 3. Please use python 3.12 or newer. Semantic Kernel has problems with older versions. `https://formulae.brew.sh/formula/python@3.13`
```bash
brew install python@3.13
python3 -m ensurepip --upgrade
```

```bash 
python3 -m venv venv

# Activate venv and install semantic-kernel
source venv/bin/activate
pip3 install semantic-kernel
```

Make a new .env file, copy the contents of .env.sample and add the environment variables

Start the program(If the environment variables are not loaded, please restart the terminal.)
```bash
python3 test-01.py
```

To exit chat type
```
exit
```
