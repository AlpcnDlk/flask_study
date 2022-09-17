<div id="top"></div>

<br />
<div align="center">
  <a href="https://github.com/AlpcnDlk/flask_study">
    <img src="img/devops.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Vagrant Flask Challenge</h3>

  <p align="center">
    DevOps, Provisioning/Vagrant
    <br />
    <a href="https://github.com/AlpcnDlk/flask_study"><strong>|Explore the docs|</strong></a>
    <br />
    <br />
    <a href="https://github.com/AlpcnDlk/flask_study">View Project</a>
    ·
    <a href="https://github.com/AlpcnDlk/flask_study/issues">Report Bug</a>
    ·
    <a href="https://github.com/AlpcnDlk/flask_study/issues">Request Feature</a>
  </p>
</div>

## About The Project

DevOps is an organizational approach that enables faster development of applications and easier maintenance of existing deployments. By enabling organizations to create stronger bonds between Dev, Ops and other stakeholders in the company, DevOps promotes shorter, more controllable iterations through the adoption of best practices, automation and new tools. 

The project is an example of DevOps logic. You can live the same experience as I do from anywhere you want. All you have to do is having a computer.

## Getting Started

! Warning !
* If you have APPLE M1 or AMD(some of them don't have drivers for Linux) processor, you may not use VirtualBox. Please try on another computer.

### Prerequisites

1. VirtualBox(Latest version)
2. Vagrant(Latest version)
3. Ansible(Latest version)
4. At least 3 GB of free disk storage 

### Installation

You should install VirtualBox first then Vagrant. 

## Usage

Clone the git repository.
```sh
   git clone https://github.com/AlpcnDlk/flask_study.git
   ```
Get into the "flask_study" folder and run Vagrant.
```sh
   vagrant up
   ```
There may be a problem occurs due to the private ip address. In that case you should change the ip address from the Vagrantfile according to your ip address which will be given in the error message.

After waiting Vagrant and Ansible doing their work, you will see all tasks completed and you are back in control of terminal. That means the project is ready to run.
[![terminalss][terminal-screenshot]]

Now all you have to do is entering your ip address to your web browser. For example if you don't change the default ip address from Vagrantfile it will be "192.168.56.21:5000". "5000" port address is given by Flask.
[![productss][product-screenshot]]

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.


## Contact

Alpcan İlhami Dalak - [@linkedin](https://www.linkedin.com/in/alpcandalak/) - alpcndlk01@gmail.com

Project Link: [https://github.com/AlpcnDlk/flask_study](https://github.com/AlpcnDlk/flask_study)


[terminal-screenshot]: img/terminal.png
[product-screenshot]: img/product1.png
