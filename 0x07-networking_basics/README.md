# Networking basics #0

## Resources

- [OSI model](https://en.wikipedia.org/wiki/OSI_model)
- [Different types of network](https://www.lifewire.com/lans-wans-and-other-area-networks-817376)
- [LAN network](https://en.wikipedia.org/wiki/Local_area_network)
- [WAN network](https://en.wikipedia.org/wiki/Wide_area_network)
- [Internet](https://en.wikipedia.org/wiki/Internet)
- [MAC address](https://whatismyipaddress.com/mac-address)
- [What is an IP address](https://www.bleepingcomputer.com/tutorials/ip-addresses-explained/)
- [Private and public address](https://www.iplocation.net/public-vs-private-ip-address)
- [IPv4 and IPv6](https://www.webopedia.com/insights/ipv6-ipv4-difference/)
- [Localhost](https://en.wikipedia.org/wiki/Localhost)
- [TCP and UDP](https://www.howtogeek.com/190014/htg-explains-what-is-the-difference-between-tcp-and-udp/)
- [TCP/UDP ports List](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
- [What is ping /ICMP](https://en.wikipedia.org/wiki/Ping_%28networking_utility%29)
- [Positional parameters](https://wiki.bash-hackers.org/scripting/posparams)

man or help:

- `netstat`
- `ping`

## OSI Model

- What it is
- How many layers it has
- How it is organized

## What is a LAN

- Typical usage
- Typical geographical size

## What is a WAN

- Typical usage 
- Typical geographical size

## What is the Internet

- What is an IP address
- What are the 2 types of IP address
- What is `localhost`
- What is a subnet
- Why IPv6 was created

## TCP/UDP

- What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
- What is the main difference between TCP and UDP
- What is a port
- Memorize SSH, HTTP and HTTPS port numbers
- What tool/protocol is often used to check if a device is connected to a network

# Requirements

## General

- Allowed editors: `vi`, `vim`, `emacs`
- All your Bash script files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass `shellcheck` without any error
- The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all your Bash scripts should be a comment explaining what is the script doing

### More Info

The second line of all your Bash scripts should be a comment explaining what is the script doing

For multiple choice question type tasks, just type the number of the correct answer in your answer file, add a new line for every new answer, example:

What is the most important position in a software company?

1- Project manager
2- Backend developer
3- System administrator

```
gpradinett@ubuntu$ cat foo_answer_file
3
gpradinett@ubuntu$
```
<sub>Source for question 1 [here](https://twitter.com/devopsreact/status/831922429215662080)

# [0-OSI_model]()
```
OSI model
```

OSI (Open Systems Interconnection) is an abstract model to describe layered communication and computer network design. The idea is to segregate the different parts of what make communication possible.

It is organized from the lowest level to the highest level:
- The lowest level: layer 1 which is for transmission on physical layers with electrical impulse, light or radio signal
- The highest level: layer 7 which is for application specific communication like SNMP for emails, HTTP for your web browser, etc

Keep in mind that the OSI model is a concept, it’s not even tangible. The OSI model doesn’t perform any functions in the networking process. It is a conceptual framework so we can better understand complex interactions that are happening. Most of the functionality in the OSI model exists in all communications systems.

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2018/6/4e6a0ad87a65d7054248.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220624%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220624T192148Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c2a97fa6035b9c39a5fac9066dc60cef48f4c37093358e4a8578880cc08304d2)

In this project we will mainly focus on:

- The Transport layer and especially TCP/UDP
- On the Network layer with IP and ICMP

The image bellow describes more concretely how you can relate to every level.
![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/9/0fc96bd99faa7941b18bcae4c5f90c6acd11791d.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220624%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220624T192148Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=047b72d60a84e21b7edf9caa5151b768077806c936109dcb5c9eba12b4567025)
Questions:

What is the OSI model?

1- Set of specifications that network hardware manufacturers must respect
2- The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology
3- The OSI model is a model that characterizes the communication functions of a telecommunication system with a strong regard for their underlying internal structure and technology

How is the OSI model organized?

1 - Alphabetically
2 - From the lowest to the highest level
3 - Randomly

