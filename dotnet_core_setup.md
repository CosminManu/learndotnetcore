# 🛠 Step-by-Step Guide to Setting Up .NET Core

## Step 1: Install .NET Core SDK
To start working with .NET Core, you need to install the SDK (Software Development Kit). Visit the [official .NET download page](https://dotnet.microsoft.com/download) and download the version suitable for your operating system.

- Choose the latest **LTS (Long-Term Support)** version for production-ready projects.
- Install the SDK by following the installer prompts.

---

## Step 2: Verify Installation
After installation, verify that .NET Core is installed correctly by opening a terminal or command prompt and typing:

```sh
dotnet --version
```

This command will display the installed version of .NET Core SDK.
Visit [this page](https://dotnet.microsoft.com/en-us/platform/support/policy/dotnet-core) to see supported versions of .NET and .Net Core

---

## Step 3: Create a New .NET Core Project
Use the command line to create a new .NET Core application. Navigate to your preferred directory and run the following command:

```sh
dotnet new console -n MyFirstApp
```

This will create a new console application named **"MyFirstApp"** with the required files and folder structure.

---

## Step 4: Run the Application
To test your application, navigate to the project directory and run the following command:

```sh
dotnet run
```

You should see the default **"Hello, World!"** message displayed in the terminal.

---

## Step 5: Install an Editor or IDE
For better productivity, consider using an Integrated Development Environment (IDE). Popular options include:

- **Visual Studio**: Fully-featured IDE for Windows and macOS.
- **Visual Studio Code**: Lightweight and cross-platform editor with excellent .NET Core support.

Install the required plugins/extensions for .NET Core to enable **IntelliSense, debugging, and other features**.

---

## Step 6: Add Dependencies
To add additional libraries or dependencies to your project, use the `dotnet add package` command. For example:

```sh
dotnet add package Newtonsoft.Json
```

This will add the **Newtonsoft.Json** library to your project, which you can use for JSON handling.

---

## Step 7: Build and Publish
To prepare your application for deployment, build and publish it using the following commands:

```sh
dotnet build
```

```sh
dotnet publish -c Release -o ./publish
```

This will generate the compiled application in the **./publish** directory, ready to deploy.

---

## 📌 Related Documentation
For more details, check out the [official .NET Core documentation](https://docs.microsoft.com/en-us/dotnet/core/).

