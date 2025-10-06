# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**OmutimaOmugabi** is a proposal project for CivLegacy Foundation - a digital "Wall of Fame" platform celebrating everyday acts of generosity in Uganda. This repository will contain the proposal website demonstrating Information Village Limited's capability to build the full platform.

## Current Structure

This is a **proposal/demonstration project** that will:
1. Showcase technical capabilities through a visually appealing HTML website
2. Be deployed via GitHub Pages (docs folder)
3. Use Tailwind CSS via CDN for styling
4. Demonstrate understanding of the OmutimaOmugabi platform requirements

## Key Reference Document

**PROJECT_REFERENCE.md** - Contains complete project requirements including:
- Platform technical specifications
- Brand colors: Primary Purple (#6852a2), Primary Orange (#faa92b)
- All deliverables and timeline
- Company profile and technical lead credentials
- Complete Terms of Reference from CivLegacy Foundation

Always reference this document when building proposal materials.

## Development Setup

This is a static HTML site using:
- Plain HTML/CSS/JavaScript
- **All third-party libraries via CDN** (Tailwind CSS, animations, icons, etc.)
- Single standalone `index.html` file

**Important Rules:**
- ALL external libraries MUST be included via CDN links
- NO npm packages or build tools
- Keep everything in a single `index.html` file for simplicity
- No build process required - files are served directly

## Deployment

**GitHub Pages Deployment:**
1. Place `index.html` in `/docs` folder
2. Configure GitHub Pages to serve from `/docs` directory in repository settings
3. Access site at: `https://<username>.github.io/<repository-name>/`
4. Note: Site will be publicly accessible even if repository is private (GitHub Free plan)

## Brand Guidelines

When creating any visual elements:
- **Primary Purple:** #6852a2
- **Primary Orange:** #faa92b
- Use culturally familiar icons and design patterns
- Ensure accessibility for users with varying digital literacy levels
- Maintain professional yet approachable aesthetic
