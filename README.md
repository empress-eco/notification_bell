<div align="center">

<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">

NotiBell is a powerful and innovative application designed to revolutionize your workflow management. By leveraging push notifications, geo-fencing, and face recognition technologies, NotiBell aims to enhance and streamline your work processes.

[Explore the Docs](https://wiki.nestorbird.com/wiki/installation-guide-notibell) | [Report a Bug](https://github.com/empress-eco/notification_bell/issues) | [Request a Feature](https://github.com/empress-eco/notification_bell/issues)

</div>

  


## About The Project

NotiBell, built over the Framework, is a custom application that allows users to send push notifications, implement workflow actions, check-in with geo-fencing, and use face recognition through its mobile application. It is available on both the [Play Store](https://play.google.com/store/apps/details?id=com.nb.notibell) and [App Store](https://testflight.apple.com/join/MtvAjKlz).

### Key Features
- Push notifications to mobile application
- Workflow actions depending on the role of logged-in user
- Face recognition for check-in with approval
- Geo-fencing for check-in with approval

## Technical Stack and Setup Instructions

### Built With
NotiBell is a Empress application and does not require any additional dependencies for Empress versions v13 and v14. For v14, HRMS is required.

### Installation
To get a development environment running, follow the steps below:

```sh
git clone https://github.com/empress-eco/notification_bell.git
cd notification_bell
bench get-app https://github.com/nestorbird/NotiBell-Empress.git --branch main
bench --site <site_name> install-app notibell
```
For a more detailed guide on installation and setup, [click here](https://wiki.nestorbird.com/wiki/installation-guide-notibell).

## Usage
Once installed, you can start using NotiBell to empower your workflow management. To get the most out of NotiBell, ensure you have properly set up the workflow and roles within your organization.

## Contribution Guidelines
We warmly welcome and appreciate contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

For more details on contributing, check out the [Issue Guidelines](https://github.com/Empress/Empress/wiki/Issue-Guidelines) and [Pull Request Requirements](https://github.com/Empress/Empress/wiki/Contribution-Guidelines).

## Support
For support, please visit [here](https://grow.empress.eco/).

## License and Acknowledgements

This project is under the MIT License. Your contributions are also licensed under the MIT License.

Special thanks to the Empress Community for their outstanding contributions and continual support. The tools they have developed form the bedrock of this project, and we are deeply grateful for their innovative work.