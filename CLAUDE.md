# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a grocery ontology built using OWL (Web Ontology Language). The ontology defines classes and relationships for grocery items and food products.

## File Structure

- `grocery.owl` - Main ontology file containing class declarations and hierarchies in OWL Manchester syntax

## Ontology Structure

The ontology uses the namespace `http://protege.stanford.edu/ontologies/groceries/` and includes:

- **Base Classes**: `GroceryItem`, `FoodStuff`, `NutritionalInformation`
- **Product-specific Classes**: Currently includes Walkers shortbread products with proper inheritance hierarchy
- **External Vocabularies**: References SKOS, FOAF, Dublin Core Terms, and Schema.org

## Working with the Ontology

When modifying the ontology:
- Follow OWL Manchester syntax formatting
- Maintain proper class hierarchies using `SubClassOf` relationships
- Keep declarations and class relationships organized
- The file uses very long lines (350+ characters) - this is normal for OWL files

## Development Commands

This is a simple ontology project with no build system or dependencies. Changes are made directly to the OWL file and committed to git.

When committing, look at the diff and summarize the differences in the commit message.