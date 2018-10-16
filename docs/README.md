# Story API MVP

> The minimum viable product for my story API

## What is Story API?
Story API MVP is a proof of concept of my grand vision for full-fledged text-based adventures through an API. The API can work on its own, but it is recommended that you have a client dedicated to running the story by generating and sending the API requests on its own.

## How does Story API work?
A story is comprised of story components. Each story has an array of ids of the leading parts of the story, and each subsequent story component has an array of ids of the following story components. This allows the story to have many paths that flow in a logical order.
