## Ultra-Wideband Swarm Ranging
The **Swarm Ranging Protocol** is a UWB-based ranging protocol that dedicates to provide a simple yet efficient ranging experience for dynamic and dense swarm networks of robots and devices. 

This repository contains the implementation of the paper:
- **Ultra-Wideband Swarm Ranging**. [Feng Shan](http://twinhorse.net/), Jiaxin Zeng, Zengbao Li, [Junzhou Luo](https://cse.seu.edu.cn/2019/0102/c23024a257045/page.htm), [Weiwei Wu](https://cse.seu.edu.cn/2019/0103/c23024a257230/page.htm). *INFOCOM 2021*. [PDF](http://twinhorse.net/papers/SZLLW-INFOCOM21p.pdf)  
- **Ultra-Wideband Swarm Ranging Protocol for Dynamic and Dense Networks**. [Feng Shan](http://twinhorse.net/), Haodong Huo, Jiaxin Zeng, Zengbao Li, [Weiwei Wu](https://cse.seu.edu.cn/2019/0103/c23024a257230/page.htm), [Junzhou Luo](https://cse.seu.edu.cn/2019/0102/c23024a257045/page.htm). *IEEE/ACM Transactions on Networking, 2022*. [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9810917)

> This repository is forked from the [official firmware by Bitcraze](https://github.com/bitcraze/crazyflie-firmware) and all our work is stored in the folder `crazyflie-firmware/src/deck/drivers/src/swarming`.  
> If you find any error, please don't hesitate to open an issue or pull request.

If you find this repository helpful for your work, please kindly cite the following paper. The BibTeX is listed below:

```
@article{shan2021ultra,
  title={Ultra-Wideband Swarm Ranging},
  author={Shan, Feng and Zeng, Jiaxin and Li, Zengbao and Luo, Junzhou and Wu, Weiwei},
  booktitle={IEEE INFOCOM 2021-IEEE Conference on Computer Communications},
  year={2021},
  organization={IEEE}
}

@article{shan2022ultra,
  title={Ultra-Wideband Swarm Ranging Protocol for Dynamic and Dense Networks},
  author={Shan, Feng and Huo, Haodong and Zeng, Jiaxin and Li, Zengbao and Wu, Weiwei and Luo, Junzhou},
  journal={IEEE/ACM Transactions on Networking},
  year={2022},
  publisher={IEEE}
}
```

## How to run it

Clone this repository:

```
git clone --recursive https://github.com/SEU-NetSI/crazyflie-firmware.git
```

Enter the `swarming` folder:

```
cd crazyflie-firmware/src/deck/drivers/src/swarming
```

Build the firmware:

```
make clean
make
```

Flash the **cf2.bin**:

```
cfloader flash path/to/cf2.bin stm32-fw
```

If you have any question, please issue the project or [email](mailto:shanfeng@seu.edu.cn) us and we will reply you soon.
## Contributors

<table>
    <tbody>
        <tr>
            <td align="center">
                <a href="https://github.com/twinhorse"><img alt="" src="https://avatars.githubusercontent.com/twinhorse"
                        width="100px;"><br><sub><b>twinhorse</b></sub></a><br><a
                    href="https://github.com/SEU-NetSI/crazyflie-firmware/commits?author=twinhorse" title="code">💻</a>
            </td> </a></td>
            <td align="center">
                <a href="https://github.com/YuchaoS"><img alt="" src="https://avatars.githubusercontent.com/YuchaoS"
                        width="100px;"><br><sub><b>YuchaoS</b></sub></a><br><a
                    href="https://github.com/SEU-NetSI/crazyflie-firmware/commits?author=YuchaoS" title="code">💻</a>
            </td> </a></td>
            <td align="center">
                <a href="https://github.com/huohaodong"><img alt=""
                        src="https://avatars.githubusercontent.com/huohaodong"
                        width="100px;"><br><sub><b>huohaodong</b></sub></a><br><a
                    href="https://github.com/SEU-NetSI/crazyflie-firmware/commits?author=huohaodong"
                    title="code">💻</a>
            </td> </a></td>
            <td align="center">
                <a href="https://github.com/RavenLite"><img alt="" src="https://avatars.githubusercontent.com/RavenLite"
                        width="100px;"><br><sub><b>RavenLite</b></sub></a><br><a
                    href="https://github.com/SEU-NetSI/crazyflie-firmware/commits?author=RavenLite" title="code">💻</a>
            </td> </a></td>
            <td align="center">
                <a href="https://github.com/aqqz"><img alt="" src="https://avatars.githubusercontent.com/aqqz"
                        width="100px;"><br><sub><b>aqqz</b></sub></a><br><a
                    href="https://github.com/SEU-NetSI/crazyflie-firmware/commits?author=aqqz" title="code">💻</a>
            </td> </a></td>            
            <td align="center">
                <a href="https://github.com/Withod"><img alt="" src="https://avatars.githubusercontent.com/Withod"
                        width="100px;"><br><sub><b>Withod</b></sub></a><br><a
                    href="https://github.com/SEU-NetSI/crazyflie-firmware/commits?author=Withod" title="code">💻</a>
            </td> </a></td>
        </tr>
    </tbody>
</table>
