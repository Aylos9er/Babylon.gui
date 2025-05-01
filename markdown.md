# Knowledge Sphere Visualization

This project is a 3D knowledge sphere visualization built with [Babylon.js](https://www.babylonjs.com/), displaying a central sphere with interconnected nodes and edges representing a knowledge graph. The frontend is a JavaScript-based web application, and the backend is a Java Spring Boot server that serves knowledge graph data from a JSON file using `java.io`.

## Features
- **3D Visualization**: A central sphere with a dynamic Node Material effect, surrounded by smaller nodes (spheres) connected by edges (tubes).
- **Interactivity**: Click nodes to log data; hover to display tooltips with node labels.
- **Data Integration**: Fetches knowledge graph data from a Java backend via a REST API.
- **Performance**: Uses instanced meshes for efficient rendering of multiple nodes.

## Tech Stack
- **Frontend**: Babylon.js (v7.34.1), JavaScript, HTML, CSS
- **Backend**: Java, Spring Boot
- **Data**: JSON file read using `java.io`
- **Tools**: Node.js (for frontend dev server), Maven (for Java backend)

## Prerequisites
- [Node.js](https://nodejs.org/) (v16 or higher)
- [Java JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (11 or higher)
- [Maven](https://maven.apache.org/) (for building the Java backend)
- A modern web browser (Chrome, Firefox, Edge)

## Setup Instructions

### Frontend (Babylon.js)
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
