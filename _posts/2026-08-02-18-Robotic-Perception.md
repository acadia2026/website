---
layout: post
title:  ""
date:   2014-06-01
caption:  Robotic Perception Workflows for Hybrid Assembly
permalink: /Robotic-Perception-Workflows
project: true
category: site-workshop
thumbnail: assets/images/workshops/acadia26-workshop_RoboticPerception.jpg

---
<span style="font-size: 24px; font-weight: bold;">Robotic Perception Workflows for Hybrid Assembly</span>

# Workshop Dates: 10/19 - 10/21
<strong>Location: <a href="https://maps.app.goo.gl/7ESkfaU28hXwvJ3Z8" target="_blank" rel="noopener noreferrer">LTU, Southfield</a></strong>
**Address:** 21000 West 10 Mile Road, Southfield, MI 48075

<p style="margin: 0; font-size: 15px; font-weight: bold;">Workshop Team</p>
<p style="margin: 0;"><strong>Jiaying Wei</strong>, Carnegie Mellon University, <a href="https://www.jiaying-wei.com/" target="_blank" rel="noopener noreferrer">JiayingWei</a></p>
<p style="margin: 0;"><strong>Joshua Bard</strong>, Carnegie Mellon University, <a href="https://joshbard.com/" target="_blank" rel="noopener noreferrer">JoshBard</a>
</p>

## Registration: Regular - $325, Student - $165
# <a href="https://www.eventbrite.com/e/acadia-2026-workshops-tickets-1994103898440?aff=oddtdtcreator" target="_blank" rel="noopener noreferrer">Registration</a>

---

## Workshop Description
This workshop belongs to the Autonomous and Hybrid Fabrication track and teaches a focused ROS-based perception-to-fabrication workflow for human-robot assembly using two reliable methods: fiducial markers and skeleton extraction for localization, pose estimation, registration, and inspection, and also supports human-encoded commands that trigger robot actions via eye-in-hand sensing. These outputs are connected to guided instructions, robot inspection, and simple real-time actions such as autonomous or human-collaborative marking for material processing and assembly. The workshop will also open to experiments with learning-based methods, such as FoundationPose and Yolov8 instant segmentation, as extensions.

Learning Objectives: Participants will learn how to build a reliable perception-to-robotic motion planning and execution workflow using fiducial markers and skeleton extraction, understand how markers can support both computational registration and human-authored robot commands, and translate sensed material data into projection, inspection, marking, and lightweight assembly actions. They will also gain exposure to how this workflow can be extended through optional machine learning-based perception methods.

Intended Outcomes: Participants will leave the workshop with a practical understanding of how tag-based perception can structure human-robot fabrication workflows. Each group will contribute to a small collective prototype by deploying the provided sensing-to-action pipeline from the workshop. Final outcomes will include physical prototypes, pose estimation/marker-based registration, and command workflows, robot-assisted inspection and documentation, and one or more material-processing actions such as autonomous marking or human-collaborative marking.

Technical Constraints: The workshop is intentionally scoped around two reliable perception methods that can be set up quickly and reliably within a three-day format. It does not depend on on-site training of machine learning models, and ML methods are included as optional exploration, with the instructor providing a computation stack with installed models such as Foundation pose and YOLOv8. The setup is based on a tested teaching infrastructure developed in Architectural Robotics with Perception at Carnegie Mellon University, using a standardized ABB IRB120 hardware/controller setup and a transferable ROS-based stack, making the workshop feasible for rapid deployment.

## Workshop Schedule

### Day 1 – Register and Read
**Time**: 10:00 am – 5:00 pm (w/ 1-hour break)
Focus: Understanding perception as both sensing and interaction

Morning: Introduction to the workshop topic, safety, and hybrid fabrication agenda. Short lecture on introduction to depth cameras, hand-in-eye robot setup, and transfer of robot perception and motion planning to design (ROS-Grasshopper) pipeline in the workshop. Demonstration of the two core methods: fiducial marker (April tags, QR codes) workflows and skeleton extraction. 

Afternoon: Participants set up and test fiducial marker workflows in both modes. Markers are used for localization, frame registration, and projection alignment. They are used as human-encoded command tokens, presented to the robot’s eye-in-hand camera to trigger actions such as inspect, return home, or move to pose-oriented task states. Participants also begin testing skeleton extraction on rod-like or linear materials. Participants will also form groups of 3-4 to use the provided Grasshopper templates to send/receive real-time poses from the camera, brainstorm desired interactions, or advance to learning-based pose estimation with CAD digital twin.

Day 1 deliverables: A working marker-based registration setup, one human-encoded marker command workflow, and one initial skeleton extraction result.


### Day 2 – Translate Perception into Assembly Logic
**Time**: 10:00 am – 5:00 pm (w/ 1-hour break)
Focus: from sensed geometry to known environment semantics and robotic assembly behaviors

Morning: Participants refine registered geometry and simplify scanned materials into centerlines or skeleton structures that can inform assembly reasoning, while Marker information is linked to predefined CAD geometries in Grasshopper, which are then processed into physical material with robot-known poses and geometries with identities in the planning scene.

Afternoon: Teams develop robotic assembly responses from sensed data. These may include placement cues, robot trajectory preview for alignment, or material-processing routines that prepare parts for assembly under robot inspections. Special emphasis is placed on how perception can support autonomous marking by the robot or human-collaborative marking, where projected and robotic cues guide manual processing before assembly. By the end of the session, teams test a baseline perception-and-execution loop that connects sensing, geometric translation, and robot action for pick-and-place or assembly preparation.

Day 2 deliverables: A perception-to-geometry digital twin workflow, a perception-triggered marking or pick-and-assembly routine, and a prototype assembly logic ready for execution

### Day 3 – Assemble and Inspect
**Time**: 10:00 am – 5:00 pm (w/ 1-hour break)
Focus: hybrid robotic assembly and collective prototype production

Morning: Final calibration and testing. Participants begin executing marker-triggered robotic assembly using the established stack. Materials are prepared and verified through robotic inspection, autonomous or human-collaborative material processing, and then moved into assembly sequences. Teams refine robot motions and interaction logic based on real-time sensing feedback.

Afternoon: Groups use the eye-in-hand robot to assemble, inspect, and evaluate the result. The workshop concludes with short presentations that show how each team translated perception into assembly logic, robotic action, and fabrication outcomes.

Day 3 final deliverables: A small collective assembly prototype for each group, a documented marker-based interaction workflow, a skeleton-based assembly geometry workflow, and robot-assisted inspection or documentation output.

**Total Workshop Time**: 18~20 hours over 3 days

## Participant Information
- **Audience**: Students, researchers, and professionals in architecture, design, and digital fabrication
- **Skill Level**: Participants are expected to be familiar with Grasshopper, and some basic knowledge with Python.
- **Group Size**: ~15 participants
- **Hardware**: laptop capable of running Rhino 8

## Workshop Gallery

{% include image-gallery.html folder="assets/images/workshops/RoboticPerseption" item_width="30%" show_caption="false" %}

## Refund and Change Policy

**Important:** Refund and change requests will not be accepted beyond Monday, October 5th.
