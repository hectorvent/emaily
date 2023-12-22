<div align="center">
  <p align="center">
      <img src="https://github.com/fredpena/emaily/assets/5680906/613a6c89-fab2-460d-b779-6aa34c519c31" width=500 height=500/>
  </p>
</div>

# Email Dispatcher Microservice

>  Under development.

The Email Dispatcher Microservice is an open-source project designed to facilitate flexible and extensible email sending. This microservice supports various communication protocols, template engines, and attachment providers.

## Contributing
Contributions are welcome! If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b new-feature).
3. Make your changes and commit them (git commit -am 'Add new feature').
4. Push your changes to your fork (git push origin new-feature).
5. Create a new Pull Request.

   
## Key Features

### Ways to Send an Email

- [ ] **Restful:** Exposing endpoints for sending emails over HTTP using RESTful principles.
- [ ] **gRPC:** Using gRPC for high-performance, language-agnostic communication.
- [ ] **AMQP Consumer (RabbitMQ / ActiveMQ):** Consuming messages from a message broker using Advanced Message Queuing Protocol.
- [ ] **Kafka Consumer:** Consuming messages from Kafka, a distributed streaming platform.

### Templates Engine

- [ ] **Apache FreeMarker:** A powerful template engine that supports a variety of template formats.
- [ ] **Jade:** A concise and expressive template language for HTML.
- [ ] **Handlebars:** A popular templating engine with a simple syntax.
- [ ] **Velocity:** A template engine for Java that allows dynamic content generation.

### Attachments Providers

- [ ] **S3:** Amazon Simple Storage Service, a scalable and secure object storage service.
- [ ] **HTTP URL (Public, Basic Auth, Bearer):** Retrieving attachments from public URLs or URLs requiring authentication.
- [ ] **Base64:** Supporting inline attachments by encoding them in Base64.
- [ ] **Local File System:** Loading attachments from the local file system.
- [ ] **FTP:** Supporting attachments hosted on FTP servers.

## Usage

### Configuration

1. Clone the repository:
   
   `git clone https://github.com/hectorvent/emaily.git`
   
2. Configure the necessary options in `config.yaml` or through environment variables.

### Examples
Below are examples of how to use the microservice:

- #### Send email via RESTful:
  `# Example code`
  
- #### Send email via gRPC:
  `# Example code`
  
- #### Send email via AMQP:
  `# Example code`
  
- #### Send email via Kafka:
  `# Example code`

## License
This project is licensed under the .... - see the LICENSE file for more details.

## Contact
For questions or suggestions, feel free to contact us at ...

[Colaboradores](https://github.com/hectorvent/emaily/graphs/contributors)
   
<a href="https://github.com/hectorvent/emaily/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=hectorvent/emaily" />
</a>
