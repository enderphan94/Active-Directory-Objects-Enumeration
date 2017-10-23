# Wiki

Here: https://github.com/enderphan94/Learn-Power-Shell/wiki

# Problems reported

Here: https://github.com/enderphan94/Learn-Power-Shell/wiki#anatomy-ldap-attributes


# Forensic: Active Directory Objects

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

- Powershell Version 4 as a minimum 
- < Windows 7/ Windows Server 2012..
- Run as regular user

```
The tool has been tested in Windows Server 2012
```

### Installing

A step by step series of examples that tell you have to get a development env running

1. Clone it to your directory:

    `https://github.com/enderphan94/ad-Tracking/`
    
2. Run as a regular user:

    `~user$:./adTracking.ps1`
    
3. Follow the prompts given from the tool

## Deployment

In order to deploy this on a live system, you don't need an Admin account. You can deploy it from the trusted Domain Controller where it's able to query the data from others needed DCs.

## Built With

1. Powershell 
2. .Net 
3. HTML5/CSS

## Versioning

Last version updated! - Version 1.2

# Usages 1.2

You just need to follow the tools instruction

- Updates:

    + Added the trusted domain method
    
    + Fixed Account expires function
    
    + Change parameters to optional methods
    
- Cool Functions:

    + Free to run the tool on current domain or trusted domain
    
    + List all trusted domain by using `Get-ADTrust` ( Windows 2012 or higher )
    
    + Able to scan un-replicated attributes. It will go to each DC's and get the most proper values
    
    + Giving out a colorful HTML report which contains information of domain, domain summary and data illustration with pie charts and bar graphs


## Authors

* **Ender Loc Phan** - *Initial work* - [GitRespo](https://github.com/enderphan94)

See also the list of [CCI-WebPage](enderphan.2wy.info) projects I have done 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
