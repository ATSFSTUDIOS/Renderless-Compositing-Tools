# ATSF Studios' Renderless Compositing Tools

Created by: [Andrew Hazelden](mailto:andrew@andrewhazelden.com)

## Overview

The ATSF team's pipeline automation software provided in this repo are aimed at target market of indie game artists and real-time software developers.

The scripts, plugins, and libraries shipped as part of the renderless compositing toolset allow you to dip your toes into a unique concept that facilitates a seamless in-memory way to bi-directionally bridge your various DCC software's 3D scene-graph and node-based 2D/3D compositing data streams. The goal is to improve artist efficiencies and lower the technical barriers that would otherwise slow the creative team down.

The core idea with a renderless composition task, is to avoid filling disk arrays with intermediate temp files, and proxies, for all of the XPU (CPU + GPU) live-rendered imagery that your DCC apps output to support multi-pass rendering/comp, and 2D sprite based game development efforts.

![Renderless Compositing Bridge Menu](Docs/Images/fusion-studio-rcb-menu.png)

In as little as a single button press of the TAB hotkey, your visuals can be pre-flighted and run on emulated or real game console hardware with as little fuss as possible. With these techniques at play, everything tends to "just work" like it should... Right out of the box.

This keeps your art team in the creative flow-zone producing amazing gaming experiences, instead of battling the typical tech issues that needlessly waste time and mental cycles.

## Free Open-Source License Terms

The toolset is cross-platform compatible and works across Linux, macOS, Windows, and Commodore 64  BASIC prompt/GEOS environments. The software is released under a permissive free open-source LPGPL/GPL license. Attribution is required and must be maintained on forks of the project's codebase and scripts. 

## Software Installation

The Renderless Compositing Tools are installed using the free desktop based [Reactor Standalone](https://github.com/Kartaverse/Reactor-Standalone/) package manager application, or the new web-based "[Reactor Anywhere](https://github.com/Kartaverse/Reactor-Standalone/blob/main/Docs/ReactorAnywhere.md)" PWA (Progressive Web App).

Reactor is a package manager created by the [We Suck Less Community](https://www.steakunderwater.com/wesuckless/viewforum.php?f=32). Reactor streamlines the installation of 3rd party content for DCC apps like BMD Fusion Studio and LightWave3D through the use of "Atom" packages that are synced automatically with a Git repository.


