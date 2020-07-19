# Pinch-Analysis-Tool-
A server-less Pinch Analysis Tool to be used by students and educators.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Currently, the only prerequisite for this project is the Rust build system. Installation instructions are available at https://rustup.rs. In summary, run:

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

and follow the interactive prompts. 

### Installing

Clone this repository, then run `cargo build` for a debug build of the project. To try out the optimized build, run `cargo build --release`.

## Running the tests

Run `cargo test`.


## Deployment

The project is currently just a Rust library, and has no standalone deployment. 

## Built With

Check back soon for this section. 

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/notthesinger/Pinch-Analysis-Tool-/tags). 

## Authors

* **James Taylor** - *Initial work* - [notthesinger](https://github.com/notthesinger)
* **Andrew Hoetker** - *Initial work* - [ahoetker](https://github.com/ahoetker)

See also the list of [contributors](https://github.com/notthesinger/Pinch-Analysis-Tool-/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Jeffrey S Umbach, whose  [Online Pinch Analysis Tool](http://uic-che.org/pinch/stream_input.php) inspired this project
* Gregory Raupp, Chemical Engineering professor at Arizona State University
