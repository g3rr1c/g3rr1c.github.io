---
layout: essay
type: essay
title: "Building Cathedrals with Blueprints: Design Patterns in Web Development"
# All dates must be YYYY-MM-DD format!
date: 2025-12-03
published: true
labels:
  - Design Patterns
---

<img width="500px" src="/img/cathedral.jpeg">

## Building Cathedrals with Blueprints
Imagine you're an architect tasked with designing a cathedral. You wouldn't start by stacking stones; instead, you'd consult centuries of architectural wisdom about how to distribute weight, create soaring arches, and let light filter through stained glass. Software design patterns work the same way in that they're architectural blueprints that prevent us from reinventing the wheel every time we build something new.

Design patterns are tried and true solutions to problems that developers constantly encounter. Christopher Alexander, the architect who first created this concept, described design patterns as solutions you can use "a million times over, without ever doing it the same way twice." Just like how certain roof designs thrive in Hawaii's tropical climate, while others would collapse under the rain, software patterns need to adapt and be tweaked to each environment. These design patterns create a fairly general and reusable solution to a commonly occurring problem in software design.


## Different Design Patterns

When building a web application, you’re essentially constructing a digital cathedral where design patterns serve as your blueprints. Almost all modern web applications rely on the Model-View-Controller (MVC) pattern, which separates your application into a backend (model), a frontend (view), and a way to communicate between the two (controller). With our final project it utilizes this exact design pattern, with Bootstrap-React as the view, a Prisma database as the model, and Next.js and route handlers as the controller. For my particular project, RIBows, the Prisma database client acts as one connection pool that all the API routes share, rather than each API route creating its own connection, which is an example of the Singleton design pattern. Utilizing multiple different design patterns helps solve difficult issues with minimal effort and ensures a smooth development process. 


## One Blueprint for All

The beauty of design patterns lies not in their rigidity but in their ability to adapt. They provide a shared language among developers and a toolkit of proven solutions, allowing us to focus on the specifics of each challenge that our specific project has, rather than reinventing basic architecture. When you combine MVC's structural clarity or the Singleton's resource efficiency, you create applications that are maintainable, scalable, and elegant digital cathedrals that can stand the test of time.
