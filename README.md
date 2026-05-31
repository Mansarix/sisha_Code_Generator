# 🚀 Sisha CRUD Generator

<p align="center">
  <b>A powerful T4-based CRUD & Admin Panel Generator for ASP.NET Core MVC</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/.NET-ASP.NET%20Core-blue" />
  <img src="https://img.shields.io/badge/T4-Code%20Generation-purple" />
  <img src="https://img.shields.io/badge/Architecture-Layered-green" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey" />
</p>

---

## ✨ Overview

**Sisha Code Generator** is a lightweight yet powerful T4-based code generator that automatically scaffolds a complete Admin Panel and CRUD architecture from your existing domain models.

It eliminates repetitive boilerplate code and helps you rapidly build structured ASP.NET Core applications.

---

## 🔥 What It Generates

For each model, the generator automatically creates:

✅ MVC Controller  
✅ API Controller  
✅ Service Layer  
✅ Repository Layer  
✅ DTOs  
✅ AutoMapper Profiles  
✅ Razor Views (Index, Create, Edit, Details, Delete)  
✅ CSV Import Support  
✅ Dependency Injection Registration  

You go from:

```
Model → Full Admin CRUD Stack
```

in seconds.

---

## 🧱 Architecture Style

The generator follows a **clean layered architecture**:

```
Presentation (MVC)
    ↓
Application (Services, DTOs)
    ↓
Infrastructure (Repositories, EF Core)
```

This keeps the project maintainable, testable, and scalable.

---

## 🚀 Getting Started

### 1️⃣ Add the Generator

Place the `.tt` file inside your ASP.NET Core project.

### 2️⃣ Configure Parameters (Optional)

Set namespaces or model paths if needed.

### 3️⃣ Run the Generator

Right-click the `.tt` file →  
Select **Run Custom Tool**

### ✅ Done!

All required CRUD layers will be generated automatically.

---

## 📦 Requirements

- .NET / ASP.NET Core MVC  
- Entity Framework Core  
- AutoMapper  
- Visual Studio (with T4 support)

---

## 📁 Example Output Structure

After generation:

```
Controllers/
Services/
Repositories/
DTOs/
Mappings/
Views/
Helpers/
```

Each model gets its own complete CRUD implementation.

---

## 🎯 Why This Project?

- ⚡ Rapid Admin Panel Development  
- 🧱 Structured Layered Architecture  
- 🔄 Reduces Repetitive Coding  
- 🛠 Demonstrates Advanced T4 Code Generation  
- 💼 Resume-Ready Engineering Project  

---

## 📸 Preview

You can add screenshots or GIF previews inside:

```
/docs/images/
```

And display them like:

```html
<p align="center">
  <img src="docs/images/admin-preview.png" width="800"/>
</p>
```

---

## 🧠 Technical Highlights

- Dynamic model parsing  
- Property extraction via Regex  
- Navigation property filtering  
- Auto file generation with banner protection  
- Layer-aware scaffolding  

---

## 👨‍💻 Author

Mahmood Ansari  

---

## 📄 License

MIT License
