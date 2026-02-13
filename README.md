# Preface

My Engineering Capstone project involving the development of an Android augmented reality image tracker for use in a mock surgical setting. The objective of this project was to explore the possibility of an augmented reality application within the context of a medical setting, specifically within the operating room. The project requirements were as follows:

- AR application using suitable AR SDK on a smartphone platform
- Virtual representations of mock patient spine and surgical tool
- AR Functionalities: spatial anchoring, object rendering, and tool movement tracking by means of image tracking methods
- GUI that facilitates interaction with the AR environment and application
- Method of evaluation for application accuracy

# Introduction

The project was developed with the 2022.3.52f1 release of [Unity 5](https://unity.com/) in conjunction with Unity's AR Foundation and Google's AR Core. The following image showcases the overall software diagram architecture:

![SAD](https://github.com/anthonyandres/Android-Unity-AR-Surgery-Image-Tracker/blob/main/Images/softwareDiagramArchitecture.jpg)

The main goal of the application was to provide a way to visualize normally obstruced viscera. The application was planned and developed under the context of using the application in a spinal surgery setting. In this setting, a surgeon would be able to physically see a portion of the spine, but through the use of the AR application would be able to visualize the entire spine as well as visualize the interaction between their surgical tool and the occluded spine sections.

<div>
  
  <img src="https://github.com/anthonyandres/Android-Unity-AR-Surgery-Image-Tracker/blob/main/Images/3dMockRender_A.jpg" alt="3diagram1" width="400"/>
  
  <img src="https://github.com/anthonyandres/Android-Unity-AR-Surgery-Image-Tracker/blob/main/Images/3dMockRender_B.jpg" alt="3diagram2" width="400"/>

  
  <img src="https://github.com/anthonyandres/Android-Unity-AR-Surgery-Image-Tracker/blob/main/Images/3dMockRender_D.jpg" alt="3diagram3" width="400"/>
  
  <img src="https://github.com/anthonyandres/Android-Unity-AR-Surgery-Image-Tracker/blob/main/Images/3dMockRender_C.jpg" alt="3diagram4" width="400"/>

</div>
<br />
Users would have the smartphone pointed at the scene in a sturdy location to ensure proper tracking of marked image trackers. An image tracker would be used for each the patient spine and the surgical tool; Both image trackers would be used as a point of reference for location in 3D space. The spine tracker would allow for the superimposition of the 3D spine model over the real world patient spine, and the tool tracker would allow for the real world surgical tool to "interact" with the superimposed 3D spine model. The interaction between the real world tool and the 3D spine model is important as it allows the surgeon to know real world distances between their tool and the occluded spine sections. 

# Important Components

This section will explain the components of the Unity project that most contribute to the overall functionality of the application.

## AR Session

## XR Interaction Manager

## XR Origin

## General Managers

## LineRenderer
