# BTools | Blazor Tools

BTools is a powerful NuGet package for Blazor that provides a collection of useful and stylish UI components. These components are easy to integrate, require minimal configuration, and look great out of the box. 😉

## 📌 Features
- Easy integration
- Modern, attractive design
- Multiple components for different use cases
- Highly customizable

---

## 🛠 Components

### 🔘 Buttons
Buttons are easy to use and available in multiple styles.

**Usage:**
```razor
<BButton Version="BButton.Ver.Secondary">Text</BButton>
```

**Available Versions:**
- `Primary` (Default)
- `Secondary`
- `Destructive`
- `Outline`

> **Note:** The `Version` attribute is required to define the button style.

---

### ⌨️ Inputs
The `BInput` component provides a simple input field.

**Usage:**
```razor
<BInput PlaceHolder="Search..." />
```

**Optional Attributes:**
- `Value="text"` → Sets a predefined text value

---

## 📦 Installation
Add the NuGet package `BTools` to your Blazor project:
```sh
 dotnet add package BTools
```

Or install it via the NuGet Package Manager UI in Visual Studio.

---

## 🚀 Usage
1. Install the package (see above).
2. Add `@using BComps.Components` to be able to place the components in your project.
3. Use the components in your Blazor project.

> **Note:** More components and features will be added soon!

---

💡 **Feedback or suggestions?** Create an issue or a pull request on GitHub!

**Happy Coding! 🚀**

