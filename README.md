<p align="center"><a href="https://alienfishconsulting.com" target="_blank"><img src="https://images2.imgbox.com/d0/fe/1YGgwXjt_o.png" width="400" alt="Alien Fish Logo"></a></p>

<p align="center">
<a href="https://packagist.org/packages/alienfish/alienfish-api"><img src="https://img.shields.io/badge/php-8.2-green" alt="License"></a>
<img src="https://img.shields.io/github/v/tag/TerryLeeAllenJr/alienfish-api" alt="Commit Activity">
<img src="https://img.shields.io/badge/tests-passing-green" alt="Tests">
<img src="https://img.shields.io/badge/build-passing-green" alt="Build">
<img src="https://img.shields.io/github/commit-activity/m/TerryLeeAllenJr/alienfish-api" alt="Commit Activity">
<a href="https://github.com/TerryLeeAllenJr/alienfish-api"><img src="https://img.shields.io/github/license/TerryLeeAllenJr/alienfish-api" alt="License"></a>
<a href="https://twitter.com"><img src="https://img.shields.io/twitter/follow/alienfish?style=social" alt="Twitter"></a>
</p>

## Alien Fish Consulting (API)

*Please note that at this time this is a work in progress, and is in it's very early stages.*

Alien Fish Digital Consulting is an open source learning, training, and digital collaboration platform founded by Lee Allen and Robert Herring in March of 2023.

___
### API Core Concepts

- Built on [Laravel](https://laravel.com) ([v.10.10.0](https://packagist.org/packages/laravel/framework#v10.10.0))
  - Leverages [Laravel Sanctum](https://laravel.com/docs/10.x/sanctum) in addition to the [AlienFish\Core](https://github.com/TerryLeeAllenJr/alienfish-laravel-core) Laravel package to provide secure authentication along with robust **P**rivilege **A**ccess **M**anagement.
  - Includes a pre-configured custom `docker-compose.yaml`file leveraging [Laravel Sail](https://laravel.com/docs/10.x/sail) for ease of environment setup. 
  - Adheres to _all_ Laravel best practices. We do not, and will **never** "hack the core."
- Leverages the [AlienFish\Events](https://github.com/TerryLeeAllenJr/alienfish-laravel-events) Laravel package to provide a scaleable, real time, event driven architecture across all applications, websites, and microservices within the Alien Fish ecosystem. 
  - _At launch time, this package will only support AWS integration._ 

___
### Installation
Coming Soon



___
## Helpful Links

Postman API [collection](https://foo.bar) + [documentation](https://foo.bar).

Laravel [documentation](https://laravel.com/docs).


## Contributing

Alien Fish aims to prove that open source is secure, efficient, and can make a lasting impact on businesses and the tech culture as a whole. We welcome, embrace, and hope that as  our community grows, more and more people will be willing to contribute. As such, all aspects of our codebase will be open source... forever. However, we will also always reserve the right to curate, modify, or flat our refuse any and all changes requested to the platform. 

This is not to discourage contribution, but to ensure code quality, the quality of our platform, and the security of our users. 

## Code of Conduct

In the spirit of open source, we ask that you conform to the Laravel [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).
Yes, we're currently too lazy to write our own... but honestly, it's just that damn good. 

## Security Vulnerabilities

We pride ourselves on being a secure, open source community. If you discover any security vulnerability with our codebase, please send an email to Lee Allen via [lee.allen.sc@gmail.com](mailto:lee.allen.sc@gmail.com). Maybe one day we can have a bounty program, but for the moment I'm too broke. I'll definatley buy you a beer (or a soda if that's your bag.)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
