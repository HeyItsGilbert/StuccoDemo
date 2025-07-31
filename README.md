# PSStucco Demo

This repository contains a demonstration of **PSStucco**, a PowerShell module that helps you create open source PowerShell modules in minutes!

## What is PSStucco?

PSStucco is a scaffolding tool that sets up a complete PowerShell module development environment with:

- Proper module structure
- Build automation with PSake
- Testing framework with Pester
- CI/CD pipeline configuration
- Documentation templates

## Demo Overview

This demo walks through the complete process of:

1. **Installing PSStucco** - Getting the module from PowerShell Gallery
2. **Setting up GitHub Repository** - Creating and configuring your repo
3. **Creating Your Module** - Using PSStucco to scaffold your project
4. **Building and Testing** - Running tests and building your module
5. **Publishing** - Deploying to PowerShell Gallery via GitHub Actions

## Getting Started

### Prerequisites

To follow along with this demo, you'll need:

- GitHub account
- Git installed
- PowerShell 5.1 or PowerShell Core 6+
- VS Code (recommended)

### Installation

Install PSStucco from the PowerShell Gallery:

```powershell
Install-Module PSStucco
```

### Quick Start

1. Create a new GitHub repository
2. Clone it locally
3. Run the module generator:

   ```powershell
   New-StuccoModule
   ```

4. Follow the prompts to configure your module

## Demo Structure

This repository includes:

- **Presentation.md** - Marp presentation slides for the demo
- **Images** - Supporting visual assets for the presentation
- **README.md** - This documentation

## Key Features Demonstrated

### Automated Project Setup

- Module manifest creation
- Folder structure organization
- Build script configuration
- Test framework setup

### CI/CD Integration

- GitHub Actions workflows
- Automated testing on pull requests
- PowerShell Gallery publishing
- Documentation generation

### Best Practices

- Proper module structure
- Unit testing with Pester
- Build automation with PSake
- Semantic versioning

## Presentation

The demo includes a Marp presentation that covers:

- Live coding demonstration
- Step-by-step walkthrough
- Best practices and tips
- Q&A session

## Authors

- **Jake Hildreth** (*aka Horse*) - [dotdot.horse](https://dotdot.horse)
- **Gilbert Sanchez** (*aka HeyItsGilbert*) - [gilbertsanchez.com](https://gilbertsanchez.com)

## Additional Resources

- [PSStucco on PowerShell Gallery](https://www.powershellgallery.com/packages/PSStucco)
- [PowerShell Gallery](https://www.powershellgallery.com/)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Pester Testing Framework](https://pester.dev/)

## Contributing

This is a demonstration repository. For contributing to PSStucco itself, please visit the main PSStucco repository.

## License

This demo content is provided as-is for educational purposes.

---

*Cover photo in presentation by [Avel Chuklanov](https://unsplash.com/@chuklanov) on [Unsplash](https://unsplash.com/photos/IB0VA6VdqBw)*
