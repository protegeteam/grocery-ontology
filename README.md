# Grocery Ontology

A comprehensive OWL (Web Ontology Language) ontology for modeling grocery items, food products, and their nutritional properties.

## Overview

This ontology defines semantic relationships between grocery items, ingredients, nutritional information, and allergen constraints. It provides a structured framework for food product classification and analysis.

## Key Features

- **Product Classification**: Hierarchical organization of grocery items including cookies, shortbreads, and other food products
- **Nutritional Analysis**: Detailed modeling of nutritional content with functional property constraints
- **Ingredient Relationships**: Complex ingredient hierarchies with allergen and dietary restriction support
- **Geographical Information**: Location-based classification with transitive properties
- **Defined Classes**: Automated classification based on nutritional thresholds (low/high sodium, sugar content, etc.)

## Ontology Structure

- **Namespace**: `http://protege.stanford.edu/ontologies/groceries/`
- **Base Classes**: `GroceryItem`, `FoodStuff`, `NutritionalInformation`
- **External Vocabularies**: SKOS, FOAF, Dublin Core Terms, Schema.org

## File

- `grocery.owl` - Main ontology file in OWL Manchester syntax

## Usage

The ontology can be opened and edited using ontology editors like Protégé or processed programmatically using OWL API libraries.