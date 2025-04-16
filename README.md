# My `/.bashrc` Setup Guide

This guide walks you through the process of setting up **ble.sh** (Bash Line Editor) for enhanced autocompletion and syntax highlighting in your terminal.
I've made a slight tweak to how the output looks and implemented a two line dynamic prompt as well.


#### Enjoy!

## Step 1:
### Cloning and compiling ble.sh

![step 1](https://github.com/user-attachments/assets/7f16375e-bd8d-41f9-aeb9-f69759a770a5)

#### First, clone the official ble.sh repository [see here](https://github.com/akinomyoga/ble.sh):
```
git clone https://github.com/akinomyoga/ble.sh.git
```

#### Then, cd into the directory:
```
cd ble.sh
```
#### Complile ble.sh using make:
```
make
```

## Step 2:
### Verify compile success and file path

![step 2](https://github.com/user-attachments/assets/c8ee1a38-6a6e-4779-b774-bc2543180a01)

#### Check for the compiled `ble.sh` file in the `out` directory:
```
ls
```
#### Change into `out` directory:
```
cd out
```
#### Make sure `ble.sh` file is there:
```
ls
```
#### Get file path for `/.bashrc`:
```
pwd
```
## Step 3:
### Setting bash script

#### Edit your `/.bashrc` script (Use whichever text editor you have installed):
```
nano ~/.bashrc
```
#### Paste the script from [.bashrc](https://github.com/dramiajr/bashrc-/blob/main/.bashrc%20script)
##### MAKE SURE `ble.sh` IS SOURCED CORRECTLY HERE 
![step3](https://github.com/user-attachments/assets/f754847e-e8a6-4aaa-b2ba-a4b19ed55717)

#### After pasting, exit the editor:
- `CTRL + X` to exit
- `Y` to save
- `Enter` to confirm and exit

## Step 4:
### Apply changes

#### You can either reload `/.bashrc` from the terminal:
```
source ~/.bashrc
```
![step4](https://github.com/user-attachments/assets/7002f586-ec5d-49de-8ce6-ee94fea12153)

#### Or just close out and open a new terminal 

## Now you should see autocompletion features and syntax highlighting enabled

### Example using terminator
![terminator](https://github.com/user-attachments/assets/61f2b007-6e62-4fef-b33a-f35797018814)

### Example using GNOME terminal
![another terminal](https://github.com/user-attachments/assets/76ab7b3c-b31a-4673-96fb-fa1859d3b9e4)

## License
This project includes source code licensed under the BSD-style license by K. Murase (akinomyoga). See the [LICENSE](./LICENSE) file for details.















