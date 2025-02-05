# TP Series - SEMI-STRUCTURED DATA

## University: Echahid Hamma Lakhdar El Oued  
**Faculty of Exact Sciences - Department of Computer Science**  
**Level:** Semester 6, Licence Computer Science  
**Date:** January 2025  
**By:** Ban Aicha Abderrhmane  

## TP01 - Student Data Representation

### Project Overview

The goal of this project is to describe students of El Oued University using an XML document. Each student has specific attributes and elements, and we will define the structure using XML, DTD, and XML Schema.

### Student Data Structure

Each student is uniquely identified by a **RegistrationNumber** (attribute) and contains the following data:

- **FirstName**: A required text value.
- **FamilyName**: A required text value.
- **Age**: A required integer between **1 and 150**.
- **Address** *(optional)*:
  - **Number**: Integer value from **0 to 999**.
  - **City**: Text value.
  - **PostalCode**: A five-digit number, starting with the **Wilaya code** (two digits), followed by a sequence number.
- **Level**: A required value among **{1L, 2L, 3L, 1M, 2M}**.
- **Speciality**: A required value among **{ComputerScience, Physics, Chemistry, Mathematics}**.
- **Average**: A required real number between **0.00 and 20.00** *(default: 0.00)*.

### Required Tasks

1. **XML Document Sample**  
   - Create an example XML document representing students of El Oued University.

2. **Document Type Definition (DTD)**  
   - Define a DTD to enforce the structure of the XML document.

3. **XML Schema (XSD)**  
   - Develop an XML Schema (XSD) to provide a precise definition of the student document format.

### Deliverables
- **students.xml**: An XML file containing student data.
- **students.dtd**: A DTD file defining the XML structure.
- **students.xsd**: An XML Schema describing the document format.

### Example of an XML Student Entry
```xml
<Students>
    <Student RegistrationNumber="12345">
        <FirstName>Ali</FirstName>
        <FamilyName>Benali</FamilyName>
        <Age>22</Age>
        <Address>
            <Number>25</Number>
            <City>El Oued</City>
            <PostalCode>39000</PostalCode>
        </Address>
        <Level>3L</Level>
        <Speciality>ComputerScience</Speciality>
        <Average>14.75</Average>
    </Student>
</Students>
```

### Guidelines
- Ensure the XML document is **well-formed** and **valid** according to the provided DTD and XSD.
- Use meaningful data for testing and validation.
- Follow best practices for XML structuring.

---

## Upcoming TPs
Future TPs will be added to this document as they are assigned. Stay tuned for updates!

Good luck with your project!

