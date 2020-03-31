# cicada
A [CI/CD application](https://en.wikipedia.org/wiki/CI/CD) built in (but not limited to) Laravel, free for anyone forever. The goal is to make it extensible for any situation, while keeping it as simple as possible for the end users.


## Getting Started

You can either deploy it [like a regular Laravel application](https://laravel.com/docs/7.x#server-requirements) on your system. However I would recommend to run this application in Docker.
TODO: create instructions when containers are ready.
```bash
docker-compose up -d
```

### Prerequisites

TODO: Hardware requirements

### Installing

TODO: setting up a pipeline

## Terms 101

 * environment - target system where the application has to be prepared for 
 * task - single action or command that needs to be performed
 * job - a group of tasks that belong together
 * stage - a group of jobs that are a step in the process when combined
 * pipeline - a complete set of stages
 * recipe - a pipeline blueprint from another user designed to quickly start building your application, which you can extend for your needs
 
 Please go to the wiki for full documentation.

## Running the tests

To run the tests, execute the `phpunit` command from your terminal.

### And coding style tests

The coding style is PSR-2 and will be validated by phpcs as such.

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors


## License

 GNU GPL V3. Which means this application can be used for any open source application, including a commercial one.

## Acknowledgments

* Inspired by [GoCD](https://www.gocd.org/)

## FAQ
no questions yet