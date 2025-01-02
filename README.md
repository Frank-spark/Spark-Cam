

---

# CNC G-code Generator for Plasma and Laser Cutting

## Project Overview

This project aims to develop a desktop application using React that imports DXF and SVG files to generate G-code for CNC plasma and laser cutting machines. The software will be optimized for Windows and macOS, focusing on imperial units to cater to the U.S. market.

### Core Features

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
  - Auto-nesting capability (optional but desired).
  - Ability to import postprocessors for multiple controllers.
  - **Project Export**: Ability to export the project in a format compatible with other CNC software or systems.
  - **Limited API**: A limited API will allow the software to be embedded into other projects, enabling functions such as opening files, exporting projects, and integrating with third-party software.

## Integration with PlanetCNC

The software will generate G-code that is compatible with **PlanetCNC** systems, specifically designed to work seamlessly with PlanetCNC's API. The output G-code will be structured to ensure compatibility with PlanetCNC’s expectations.

### PlanetCNC Integration Details:
- The G-code format will follow PlanetCNC's standard to ensure that it is accepted by the PlanetCNC system without modification.
- After generating the G-code, the software will integrate with PlanetCNC’s API to open the G-code in PlanetCNC for immediate use.
- A custom **M command** will be developed to handle operation-specific functions such as:
  - **Height Control**: Managing and adjusting the height of the cutting tool.
  - **Focusing**: Adjusting focus for optimal laser cutting.
  - **Material Seek (Touch-Off)**: Automatically detecting the material surface to establish the correct reference height.

For more information on PlanetCNC and their software, visit the official website: [PlanetCNC](https://www.planetcnc.com/).

## Software Examples

To gain insight into the functionality and features that our software aims to support, the following open-source and commercial tools are relevant references:

- **ProMa's MyPlasm Software**: [ProMa MyPlasm Software](https://www.proma.com.pl/en/myplasm/)
- **Cyptcut**: [Cyptcut](http://www.cyptcut.com/)
- **SheetCam**: [SheetCam](https://www.sheetcam.com/)
- **SVGnest**: [SVGnest](https://svgnest.com/)
- **Deepnest**: [Deepnest](https://deepnest.io/)

These tools provide similar functionality for plasma, laser cutting, and nesting operations.

## Coding Standards and Best Practices

Adhering to coding standards ensures maintainability and consistency across the project. Key practices include:

- **Consistent Naming Conventions**: Use descriptive and consistent names for variables, functions, and classes.
- **Modular Code**: Break down the code into small, reusable components.
- **Commenting and Documentation**: Provide clear comments and documentation to explain the functionality of the code.
- **Error Handling**: Implement robust error handling for edge cases and user input.
- **Version Control**: Use Git for version control to track changes and collaborate effectively.

## Licensing

This project is licensed under the **Spark Robotic License**. By contributing, you agree to the terms outlined in the license.

## Contribution Guidelines

Contributions are welcome! Please follow these guidelines:

- **Code of Conduct**: Be respectful and considerate in all interactions.
- **Pull Requests**: Submit pull requests for review.
- **Issue Reporting**: Use the issue tracker for reporting bugs or suggesting new features.

## Non-Disclosure Agreement (NDA)

Before contributing, all developers must sign a **Non-Disclosure Agreement (NDA)** to protect proprietary information.



For further inquiries or support, please contact the Spark Robotic development team at [support@sparkrobotic.com](mailto:support@sparkrobotic.com).

---

