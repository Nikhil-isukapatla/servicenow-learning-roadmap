# Table Inheritance

## Overview

ServiceNow uses table inheritance to reduce duplication and maintain consistency across applications.

## Table Hierarchy

```text
Task
├── Incident
├── Problem
├── Change Request
├── Catalog Task
└── HR Case
```

## Benefits

- Reuse common fields
- Reduce duplicate data
- Easier maintenance
- Consistent data model
- Faster application development

## Example

The Incident table automatically inherits fields such as:

- Number
- State
- Assigned To
- Priority
- Assignment Group
- Short Description

Developers only add fields that are specific to incidents.

## Key Learning

Table inheritance allows child tables to inherit fields and functionality from their parent table, making application development easier and more organized.
