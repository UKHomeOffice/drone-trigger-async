# drone-trigger-async
A proxy drone-trigger allowing a full CD pipeline to be broken down into reusable chunks.

## Usage
The `drone.io` pipeline in this project is intended to be used by another [drone.io enabled] project. 
The aim is to allow the dependent project to `drone-trigger` this pipeline, and complete its own pipeline, so that the dependent pipeline can trigger itself (by proxy of `drone-trigger-async`).

## Acknowledgements
 - [drone.io](http://docs.drone.io/)
 - [drone-trigger](https://github.com/UKHomeOffice/drone-trigger)
