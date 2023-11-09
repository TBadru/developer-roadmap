# Bump

Bump mapping is a technique in computer graphics for simulating bumps and wrinkles on the surface of an object. This is achieved by modifying the surface normals of the object and using the modified normals during lighting calculations. The result is an apparently bumpy surface rather than a smooth surface, despite the surface geometry being unchanged. Normal maps, which are a type of bump map, store the perturbations of the surface normals in an RGB image. When applied to a model, they can greatly enhance the level of perceived detail without increasing the polygon count. To emphasize, bump mapping doesn't change the geometry of the model, only the lighting calculations across its surface.