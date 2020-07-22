# Mash v1.0

## YouTube : cometolearn

## Moded by : C-T-L

Capturing audio (.wav) from target using a link

![hello](https://github.com/c-t-l/Say-Hello/blob/master/IMG_20200722_081219.jpg)

### How it works?

After the user grants microphone permissions, a website redirect button of your choice is released to distract the target while small audio files (about 4 seconds in wav format) are sent to the attacker.

It uses Recorderjs, plugin for recording/exporting the output of Web Audio API nodes (https://github.com/mattdiamond/Recorderjs)

### Features:

Port Forwarding using Ngrok

## Legal disclaimer:

Usage of SayHello for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

## Steps For Ngrok :

Go To https://ngrok.com/ and Sign in Or Sign Up 
Then Click "Download ARM Ngrok" After Downloading Extract It into /sdcard
now open your Termux And Type Command

```
cd /sdcard
mv ngrok $HOME
cd
chmod +x ngrok
Paste Ngrok Auth Token E.g ./ngrokxxxxxxxxxxxxxxxxxxx
cp ngrok Mash

```

### Usage Commands:

```

pkg Install git -y

pkg install php -y

git clone https://github.com/thelinuxchoice/sayhello

cd sayhello

bash sayhello.sh

select port 2 ngrok

```

### Donate!

Support the authors:

### Bitcoin:

19VMLVLtzkmc9qS4mnNob35bTF6ujx1J8U
