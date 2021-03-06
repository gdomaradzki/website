+++
title = "GSAIRigidBody2DAgent"
description = "A specialized steering agent that updates itself every frame so the user does\n not have to using a RigidBody2D"
author = "razoric"
date = "2020-02-11"
+++

<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

**Extends:** GSAISpecializedAgent

## Description ##

A specialized steering agent that updates itself every frame so the user does
 not have to using a RigidBody2D

## Properties ##

Type | Name
 --- | --- 
RigidBody2D | body

## Methods ##

Type | Name
 --- | --- 
void | func _apply_steering(acceleration: GSAITargetAcceleration, _delta: float) -> void

## Property Descriptions ##

### body ###

{{< highlight gdscript  >}}var body: RigidBody2D{{< / highlight >}}

Setter | _set_body

The RigidBody2D to keep track of

## Method Descriptions ##

### \_apply\_steering <small>(virtual)</small> ###

{{< highlight gdscript  >}}func _apply_steering(acceleration: GSAITargetAcceleration, _delta: float) -> void{{< / highlight >}}

Moves the agent's `body` by target `acceleration`.