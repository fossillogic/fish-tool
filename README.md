# **Fossil Tool**

Fossil Tool is a versatile, cross-platform, command-line utility designed to provide comprehensive monitoring, diagnostics, and management of system resources, processes, network, and hardware health. It is ideal for both system administrators and power users who need an efficient way to monitor their system's health and performance without relying on graphical interfaces. This tool integrates multiple functionalities into a single, unified command-line interface, making it an essential utility for both troubleshooting and proactive monitoring of system status.

## **Prerequisites**

Ensure you have the following installed before starting:

- **Meson Build System**: This project relies on Meson for its build process. For installation instructions, visit the official [Meson website](https://mesonbuild.com/Getting-meson.html).

## **Setting Up Meson Build**

1. **Install Meson**:
    - Follow the installation guide on the [Meson website](https://mesonbuild.com/Getting-meson.html) for your operating system.

## **Setting Up, Compiling, Installing, and Running the Project**

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/fossillogic/fossil-tool.git
    cd fossil-tool
    ```

2. **Configure the Build**:

    ```sh
    meson setup builddir
    ```

3. **Compile the Project**:

    ```sh
    meson compile -C builddir
    ```

4. **Install the Project**:

    ```sh
    meson install -C builddir
    ```

5. **Run the Project**:

    ```sh
    fossil-tool
    ```

## **Contributing**

Interested in contributing? We welcome contributions! Please feel free to open pull requests or create issues on the [Fossil Tool GitHub repository](https://github.com/fossillogic/fossil-tool).

## **Feedback and Support**

If you encounter issues or have questions, or would like to provide feedback, please open an issue on the [Fossil Tool GitHub repository](https://github.com/fossillogic/fossil-tool/issues).

## **License**

This project is licensed under the [Mozilla Public License](LICENSE).
