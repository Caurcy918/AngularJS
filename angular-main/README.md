<h1 align="center">Angular - The modern web developer's platform</h1>

<p align="center">
  <img src="adev/src/assets/images/press-kit/angular_icon_gradient.gif" alt="angular-logo" width="120px" height="120px"/>
  <br>
  <em>Angular is a development platform for building mobile and desktop web applications
    <br> using TypeScript/JavaScript and other languages.</em>
  <br>
</p>

<p align="center">
  <a href="https://angular.dev/"><strong>angular.dev</strong></a>
  <br>
</p>

<p align="center">
  <a href="CONTRIBUTING.md">Contributing Guidelines</a>
  ·
  <a href="https://github.com/angular/angular/issues">Submit an Issue</a>
  ·
  <a href="https://blog.angular.io/">Blog</a>
  <br>
  <br>
</p>

<p align="center">
  <a href="https://circleci.com/gh/angular/workflows/angular/tree/main">
    <img src="https://img.shields.io/circleci/build/github/angular/angular/main.svg?logo=circleci&logoColor=fff&label=CircleCI" alt="CI status" />
  </a>&nbsp;
  <a href="https://www.npmjs.com/@angular/core">
    <img src="https://img.shields.io/npm/v/@angular/core.svg?logo=npm&logoColor=fff&label=NPM+package&color=limegreen" alt="Angular on npm" />
  </a>&nbsp;
  <a href="https://discord.gg/angular">
    <img src="https://img.shields.io/discord/463752820026376202.svg?logo=discord&logoColor=fff&label=Discord&color=7389d8" alt="Discord conversation" />
  </a>
</p>

<p align="center">
  <a href="https://app.circleci.com/insights/github/angular/angular/workflows/default_workflow?branch=main">
    <img src="https://dl.circleci.com/insights-snapshot/gh/angular/angular/main/default_workflow/badge.svg" alt="InsightsSnapshot" />
  </a>
</p>

<hr>

## Documentation

Get started with Angular, learn the fundamentals and explore advanced topics on our documentation website.

- [Getting Started][quickstart]
- [Architecture][architecture]
- [Components and Templates][componentstemplates]
- [Forms][forms]
- [API][api]

### Advanced

- [Angular Elements][angularelements]
- [Server Side Rendering][ssr]
- [Schematics][schematics]
- [Lazy Loading][lazyloading]
- [Animations][animations]

### Local Development

To contribute to Angular docs, you can setup a local environment with the following commands:

```bash
# Clone Angular repo
git clone https://github.com/angular/angular.git

# Navigate to project directory
cd angular

# Install dependencies
yarn

# Build and run local dev server
# Note: Initial build will take some time
yarn docs
```

## Development Setup

### Prerequisites

- Install [Node.js] which includes [Node Package Manager][npm]

### Setting Up a Project

Install the Angular CLI globally:

```
npm install -g @angular/cli
```

Create workspace:

```
ng new [PROJECT NAME]
```

Run the application:

```
cd [PROJECT NAME]
ng serve
```
