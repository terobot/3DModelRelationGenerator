# 3DModelRelationGenerator

3D model relation generation using AI idea to share for the Building AI course.

## Summary

Idea is to take 3D objects and create relationships between the objects in 3D space using AI. Final results of generated new object can be a game character, a car, a mech, or a plane for example. First sub 3D objects are gategorized (this could also be done with machine learning) and each object have a certain interface in each gategory. Secondly code would try to produce desired assemblies out of these gategorized objects. Idea is to do this in Blender for this experiment. 


## Background

Generative AI methods so far have been mostly used to generate a single 3D object. There could be use cases for generated assemblies or 3D models consisting of several sub objects as well. Couple of these use cases are listed below with brief explanation:
* Procedural proto game assets out of pre-defined collection(s) of sub objects without defining/maintaining formulas and rules 
* Use as a quick random starting point for a 3D model design
* Mass customized product configurator without defining/maintaining selection conditions


## How is it used?

At the moment time to work on this experiment is limited, so the example code may follow later once more time to work on this. Feel free to use the idea and build it, if interested. The usage concept is explained below.

Usage:

Setting up the generator model for certain type of 3D models. (Later idea would be to figure out how to customize this for specific need)
  *  User could create new 3D objects respecting instructed interface definitions and save them in instructed way into a certain .blend file.
  *  User could re-train the model

User opens generator and define wanted type of model and wanted parameters.

Generator creates 3D model out of sub objects and shows generated 3D model for the user in Blender.


## Data sources and AI methods
Data is generated manually at first at least to get going. Most promising approach for creating this generator is Hindsight Experience Replay (HER) (https://arxiv.org/pdf/1707.01495.pdf). This would allow multi-goal setting needed for this generator, since user may want a sport car or a family wagon for example.

## Challenges

This experiment will require objects to be categorized and each object need to have a certain interface. This project is not going to solve the challenge to have objects without pre-defined interfaces placed correctly in 3D space to form a new model by AI.

Time available for this experiment is a limiting factor at the moment. This project will be at first limited to Blender environment. Most likely to keep training times feasible amount of different type of 3D models, input parameters and amount of sub 3D objects is rather limited.

## What next?

Next step would be to start building the model and modeling some amount of 3D objects. Anyone interested to help are welcome to contribute.


## Sources of inspiration

* Procedural model generators 
* Generative models (search for GAN)
* Product configurators
