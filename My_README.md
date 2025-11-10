# Vision to Reality: Single-Image 3D Object Reconstruction with Augmented Reality

**Team Members: Abhineswari M, Vishali Sharma (Vellore Institute of Technology, Chennai)**

This project utilizes TripoSR, a state-of-the-art, open-source model for high-accuracy 3D object reconstruction from a single image. For augmented reality integration and visualization, Spark AR Studio is employed to seamlessly place and interact with reconstructed 3D objects within real-world environments.

- **Note** : Meta Spark’s platform of third party tools and content will no longer be available effective January 14, 2025. After this date, users will no longer be able to log in to the platform, and the third-party AR filters will be removed from Meta's apps like Instagram and Facebook. Meta's first-party AR effects will remain available for use.

Steps for Implementation
1. 3D Reconstruction with TripoSR
- Input a single 2D object image into the TripoSR model to rapidly generate a detailed 3D mesh.
- Follow the official workflow for **TripoSR**, a state-of-the-art open-source model for **fast** feedforward 3D reconstruction from a single image, collaboratively developed by [Tripo AI](https://www.tripo3d.ai/) and [Stability AI](https://stability.ai/).

2. Model Refinement in Blender
- Import the generated mesh into Blender to clean, optimize, and enhance the 3D model’s details and textures.

3. AR Integration with Spark AR Studio
- Import the refined 3D model into Spark AR Studio for precise placement, scaling, and interaction within real-world augmented reality environments.
