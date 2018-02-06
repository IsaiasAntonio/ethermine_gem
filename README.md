# Ethermine API

This is my first gem, the gem gets the information from a miner using his Miner id, also
you can check what miners are mining, here: https://ethermine.org/

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Installing

you need to install the gem using this command:

```
gem install ethermine
```
if are having troubles installing the gem on ubuntu systems, you can run this command:

```
sudo gem install ethermine
```
##Usage 

you can create an instance of the class like here:

```
miner = Ethermine::Api::APIMiner.new("cb8f6b5fcc619e938526c0d6e978ee6c577d789b")
```
now you can access to all methods of the APIMiner class 

## Authors

* **Isaias Orozco** - https://github.com/IsaiasAntonio


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
