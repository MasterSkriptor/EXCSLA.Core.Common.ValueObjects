# EXCSLA.Core.Common.ValueObjects

Common Value Objects for Domain Entities

## Installation
You can install this package in the following ways:

1. Dotnet CLI
> dotnet add package EXCSLA.Core.Common.ValueObjects --version 1.0.1

2. Add to csproj file.
> \<PackageReference Include="EXCSLA.Core.Common.ValueObjects" Version="1.0.1" /\>

3. Visual Studio Package Manager
> NuGet\Install-Package EXCSLA.Core.Common.ValueObjects -Version 1.0.1

## Description
This package contains the following value objects to assist in creating Entities in any c# based application. They are designed to be created once and never updated, as per guidlines of Domain Driven Design and clean architecture.

### ValueObject
Base class for Value objects. This class overrides equal operatore for checking equality based off of all fields in the class. This code was sourced from the following link:
[https://github.com/jhewlett/ValueObject](https://github.com/jhewlett/ValueObject).

### FullName
FullName is a standard human name value object.

### Email
A standard email address value object.

### PhoneNumber
A standard US based phone number.

### FileName
A standard file name, with file name and extension.

### Address
The Address value object is designed to be a standard US based street address.
