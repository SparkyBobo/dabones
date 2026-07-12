# DaBones System Architecture

## Purpose

This document describes the overall system architecture of DaBones.

It captures the relationships between subsystems and the design intent behind the show platform.

## System Overview

DaBones is an integrated embedded control and performance system.

Major subsystems include:

* Show control
* Character animation
* Lighting
* Audio synchronization
* Mechanical systems
* Stage infrastructure
* Effects

## Show Control

The show requires coordination between:

* Music playback
* Character actions
* Lighting events
* Special effects

The exact implementation will continue to evolve as the system matures.

## Character Systems

Each character consists of:

* Mechanical structure
* Motion mechanisms
* Electronics
* Embedded control
* Lighting elements where appropriate

Characters currently include:

* Joey
* Slash
* Beats
* Tickles
* Lizzy
* Witches

## Lighting System

The lighting system includes:

* DMX-controlled fixtures
* Custom DMX hardware
* Lighting grid/truss structure
* Playback/control software

The lighting platform is largely functional and will be integrated into the v1.0 show.

## Electronics Platform

Character electronics will use reusable controller designs where possible.

Shared hardware and firmware platforms reduce duplication and improve maintainability.

## Audio / MIDI

The show includes audio playback and MIDI-based synchronization.

The MIDI controller system is part of the show control architecture.

## Mechanical Systems

Mechanical design includes:

* Character frames
* Motion mechanisms
* Mounting systems
* Stage structures

Mechanical reliability is a primary release constraint.

## Design Principles

* Prefer reusable platforms
* Capture decisions
* Separate experiments from releases
* Build reliable systems before adding features
