# Spark Robotic CNC G-code Generator

## Overview

This project aims to develop a desktop application using React that imports DXF and SVG files to generate G-code for CNC plasma and laser cutting machines. The application will be optimized for Windows and macOS, focusing on imperial units to cater to the U.S. market.

## Core Features

- **File Import and Conversion**:
  - Import DXF and SVG files.
  - Generate G-code compatible with CNC plasma and laser controllers.

- **Path Optimization**:
  - Offset both internal and external contours.
  - Implement lead-in and lead-out placements.
  - Perform collision detection and avoidance.
  - Support overcut functionality.

- **Project Management**:
  - Allow multiple files to be imported into a single project.
  - Enable co-edging of objects within profiles.

- **Additional Features**:
  - Support for objects inside profiles.
  - Auto-nesting capability.
  - Ability to import postprocessors for multiple controllers.
  - Project export functionality.
  - Limited API for embedding the software into other projects.

## Reference Software

- **SheetCam**: A reference for functionality.
- **ProNest**: Auto-nesting software by Hypertherm.

## Open Source Nesting Software

For insights into nesting algorithms and functionalities, consider exploring the following open-source projects:

- **Deepnest**: An open-source nesting application suitable for laser cutters, plasma cutters, and other CNC machines. 
- **SVGnest**: A free and open-source vector nesting tool for CNC machines, lasers, and plasma cutters. 

## Coding Standards and Best Practices

Adhering to coding standards is crucial for maintainability and collaboration. Key practices include:

- **Consistent Naming Conventions**: Use descriptive and consistent names for variables, functions, and classes.
- **Code Modularity**: Break down code into small, reusable functions or classes.
- **Commenting and Documentation**: Provide clear comments and documentation to explain complex logic.
- **Error Handling**: Implement robust error handling to manage exceptions gracefully.
- **Version Control**: Utilize version control systems like Git for code management.

For a comprehensive guide on coding standards, refer to LambdaTest's article on [Coding Standards and Best Practices](https://www.lambdatest.com/learning-hub/coding-standards). 

## Licensing

This project is licensed under the Spark Robotic License. By contributing, you agree to the terms outlined in the license.

## Contribution Guidelines

Contributions are welcome. Please adhere to the following guidelines:

- **Code of Conduct**: Be respectful and considerate in all interactions.
- **Pull Requests**: Submit pull requests for review.
- **Issue Reporting**: Use the issue tracker for reporting bugs or suggesting features.

## Non-Disclosure Agreement (NDA)

Before contributing, all developers must sign a Non-Disclosure Agreement (NDA) to protect proprietary information.

Here is the updated "Getting Started" section without assuming specific technologies like Node.js, but instead focusing on documenting and explaining the dependencies for the end code:

---

## Getting Started

To set up the project and start development, follow these steps to install and configure the necessary dependencies. All required dependencies should be thoroughly documented with explanations for their purpose.

### 1. Clone the Repository

Begin by cloning the repository to your local machine:

```bash
git clone https://github.com/SparkRobotic/CNC-Gcode-Generator.git
```

### 2. Install Dependencies

The project may rely on various libraries, frameworks, or tools. These dependencies need to be documented in detail, explaining their function in the project and why they are necessary. Each dependency must be listed along with a description of its role in the project.

- **List of Required Dependencies:**
  - For example:
    - **Library/Framework 1**: Description of the purpose and why it's necessary.
    - **Library/Framework 2**: Another description explaining the usage.
    - **Tool 1**: Explanation of tools required for building or running the project.
  
Provide instructions on how to install each dependency. The installation method could vary depending on the dependency type (e.g., package manager, manual installation, etc.).

**Example**:
- If using a package manager, include commands like:
  
  ```bash
  [appropriate package manager] install [dependency]
  ```

- If a tool needs to be manually installed, provide a link and detailed steps.

### 3. Running the Application

Once the dependencies are installed, the next step is to run the application. Provide clear instructions for how to launch the application, including any setup that may be necessary before running.

- **Example**: To run the application, you might use a command like:

  ```bash
  [appropriate command to start the application]
  ```

Make sure the user knows where to access the application once it is running, such as through a specific port or directory.

### 4. Additional Setup or Configuration

If there are any special configuration steps (such as environment variables, external integrations, or platform-specific setups), they should be clearly documented. Include all the necessary details to ensure the application can be successfully set up and run without issues.

For example:
- **Environment Variables**: If the project requires any environment variables, explain which ones need to be set and provide sample values.
- **External Tools or Services**: If the project integrates with third-party services or APIs, include setup instructions and credentials setup.

---

