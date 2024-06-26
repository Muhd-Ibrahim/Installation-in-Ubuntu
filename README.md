# Installation-in-Ubuntu
### Install al quran - green tech
To install the Quran app from the `org.gtaf.quran.flatpakref` file in Ubuntu, you'll need to follow these steps:

1. **Install Flatpak**: If Flatpak is not already installed on your system, you need to install it first.

    ```sh
    sudo apt update
    sudo apt install flatpak
    ```

2. **Add the Flathub repository**: Most Flatpak applications are available on Flathub. This command ensures you have access to the repository:

    ```sh
    sudo flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
    ```

3. **Download the `.flatpakref` file**: Make sure you have the `org.gtaf.quran.flatpakref` file downloaded to your computer. If you don't have it yet, download it from a trusted source.

4. **Install the Flatpakref file**: Navigate to the directory where you downloaded the `org.gtaf.quran.flatpakref` file and run the following command to install it:

    ```sh
    flatpak install org.gtaf.quran.flatpakref
    ```

5. **Run the application**: Once installed, you can run the application using Flatpak:

    ```sh
    flatpak run org.gtaf.quran
    ```

These steps should help you install and run the Quran app on your Ubuntu system. If you encounter any issues, ensure that all dependencies and repositories are correctly configured, and try again.

### Install openbangla keyboard 
### install bash
```sh
    sudo apt install bash
```

