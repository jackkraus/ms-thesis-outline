
## Abstract

## Chapter 1 - Introduction
### 1.1 - Particle Physics and the Standard Model
### 1.2 - Computational Challenges in Particle Physics
- Storage
- Memory Usage
- Computational Power
- Analysis Pipelines
### 1.3 - Objectives / Insights
- Make analysis as easy as possible without sacrificing rigor
- Either make constraints on searches or (what else??)
## Chapter 2 - LHC and  the ATLAS Experiment

### 2.1 - The Large Hadron Collider

### 2.2 - The ATLAS Experiment

### 2.3 - Data Acquisition and Processing 
- Reconstruction
- Derivation and it's issues
### 2.4 - High-Luminosity LHC Upgrade
- Why HL-LHC is happening? 
#### 2.4.1 - Run 4 Computational Challenges
- Where to put R&D and why
- Solutions: Traineeships, Analysis Grand Challenge, etc.
## Chapter 3 - ATLAS Software Framework

### 3.1 - Software Workflow
#### 3.1.1 - Overview *(why it's important/interesting)*

#### 3.1.2 - Development Cycle *(How changes are made to the framework)*

### 3.2 - ROOT and Athena *(explain how they work together)*

### 3.3 - xAOD Event Data Model 
## Chapter 4 - Derivation Production Optimization

#### 3.3.1 - Current Derivation Framework *(ROOT and Athena currently work how?)*

#### 3.3.2 - Optimization Techniques *(What we looked at in particular and why we thought it would work? Toy Model)*

#### 3.3.3 - Performance Metrics and Benchmarking *(RSS/PSS for memory usage and output file size for disk usage)*

#### 3.3.4 - Results and Discussion *(tables and charts)*

## Chapter 5 - Modernizing I/O Tests with xAOD EDM

### 5.1 - xAOD EDM Format

#### 5.1.1  - Overview
- What is the xAOD EDM
- Why is it useful for HL-LHC
- **How does it work**
#### 5.1.2 - Building xAOD::ExampleElectron
- How it was built
- What are the essential bits to take away
- How can this section help others build their own xAOD::ExampleElectron
### 5.2 - Testing xAOD::ExampleElectron
 - Writing from Tracks
 - Reading from a written ROOT file
### 5.3 -  Implementing I/O Tests into the Athena Nightly CI Build
