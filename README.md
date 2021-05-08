![GitHub](https://img.shields.io/github/license/jenkinsci/select2-api-plugin)
![GitHub pull requests](https://img.shields.io/github/issues-pr/jenkinsci/select2-api-plugin)
![Open GitHub issues](https://img.shields.io/github/issues/jenkinsci/select2-api-plugin)
![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/jenkinsci/select2-api-plugin/GitHub%20CI/master?label=GitHub%20CI)
[![Build Status](https://ci.jenkins.io/buildStatus/icon?subject=Jenkins%20CI&job=Plugins%2Fselect2-api-plugin%2Fmaster)](https://ci.jenkins.io/job/Plugins/job/select2-api-plugin/job/master/)
![Contributions](https://img.shields.io/badge/contributions-welcome-orange)
![Jenkins Plugins](https://img.shields.io/jenkins/plugin/v/select2-api?label=latest%20version)

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a id="select2" href="#select2" aria-hidden="true"><img src="https://select2.org/user/pages/images/logo.png" alt="Select2" width="100" /></a>

  <h1 align="center">Select2.js Jenkins Plugin</h1>

  <p align="center">
    Jenkins plug-in that provides <a href="https://select2.org">Select2.js</a>.
    <br />
    <a href="https://github.com/jenkinsci/select2-api-plugin/blob/master/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jenkinsci/select2-api-plugin/issues">Report Bug</a>
    ·
    <a href="https://github.com/jenkinsci/select2-api-plugin/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## Usage

In order to use this JS library, add a maven dependency to your pom:

```xml
<dependency>
  <groupId>io.jenkins.plugins</groupId>
  <artifactId>select2-api</artifactId>
  <version>[latest version]</version>
</dependency>
```

Then you can use Select2.js in your jelly files using the following snippet:

```html
<st:adjunct includes="io.jenkins.plugins.select2"/>
```

## Contributing

Contributions are what make the open source community such an amazing place to be learn,
inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

## Contact

Simon Symhoven - post@simon-symhoven.de

Project Link: [https://github.com/jenkinsci/select2-api-plugin](https://github.com/jenkinsci/select2-api-plugin)
