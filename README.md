# Hello and welcome to Positiva the best eco blog from Cali!

```YAML
  _   _   _   _   _   _   _   _               ▲
 / \ / \ / \ / \ / \ / \ / \ / \ 
| p | o | s | i | t | i | v | a |
 \_/ \_/ \_/ \_/ \_/ \_/ \_/ \_/ 
· █▀▀ █▀█ █   █ · █▀▀ █▀█ █   █ ·
· █   █▄█ █   █ · █   █▄█ █   █ ·
· █▄▄ █ █ █▄▄ █ · █▄▄ █ █ █▄▄ █ ·

```

Incorporating eco-conscious practices, informative outreach, and a commitment to enhancing the environment seamlessly into a life of well-being with

[positiva CALI][https://positiva-cali.vercel.app/]

## Nice Commands

### Running and Building commands

- hugo

- hugo -d /

- hugo serve

- git reflog

### Local server

- npm install -g http-server

next, to serve locally just run the next command in project root:

- http-server

## Installation

Install Hugo from a [prebuilt binary], package manager, or package repository. Please see the installation instructions for your operating system:

- [macOS]
- [Linux]
- [Windows]
- [DragonFly BSD, FreeBSD, NetBSD, and OpenBSD]

## Build from source

Hugo is available in two editions: standard and extended. With the extended edition you can:

- Encode to the WebP format when processing images. You can decode WebP images with either edition.
- Transpile Sass to CSS using the embedded LibSass transpiler. The extended edition is not required to use the Dart Sass transpiler.

Prerequisites to build Hugo from source:

- Standard edition: Go 1.19 or later
- Extended edition: Go 1.19 or later, and GCC

Build the standard edition:

```text
go install github.com/gohugoio/hugo@latest
```

Build the extended edition:

```text
CGO_ENABLED=1 go install -tags extended github.com/gohugoio/hugo@latest
```

## Documentation

Hugo's [documentation] includes installation instructions, a quick start guide, conceptual explanations, reference information, and examples.

Please submit documentation issues and pull requests to the [documentation repository].

## Support

Please **do not use the issue queue** for questions or troubleshooting. Unless you are certain that your issue is a software defect, use the [forum].

Hugo’s [forum] is an active community of users and developers who answer questions, share knowledge, and provide examples. A quick search of over 20,000 topics will often answer your question. Please be sure to read about [requesting help] before asking your first question.

## Contributing

You can contribute to the Hugo project by:

- Answering questions on the [forum]
- Improving the [documentation]
- Monitoring the [issue queue]
- Creating or improving [themes]
- Squashing [bugs]

Please submit documentation issues and pull requests to the [documentation repository].

If you have an idea for an enhancement or new feature, create a new topic on the [forum] in the "Feature" category. This will help you to:

- Determine if the capability already exists
- Measure interest
- Refine the concept

If there is sufficient interest, [create a proposal]. Do not submit a pull request until the project lead accepts the proposal.

For a complete guide to contributing to Hugo, see the [Contribution Guide](CONTRIBUTING.md).

# Busybox (WSL package)

In WSL 2, you can also use Busybox, a set of utilities that includes an HTTP server. If you don't have Busybox installed, you can do so with the following command:

sudo apt update
sudo apt install busybox
Then, to start the HTTP server, navigate to your project folder and execute the following command:

busybox httpd -p 8080
