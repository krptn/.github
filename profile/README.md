# Krptn

A user authentication and access management system (IAM) with [Zero Knowledge security](https://www.krptn.dev/news/zero-knowledge/). It is available as a python extension module.

How we achieve this?

- Any data can be encrypted by the developer using Krptn (not just user accounts)
- Only the appropriate users' credentials can unlock the cryptosystem (this protects you from server-side attacks)

This gives you zero knowledge security without ever needing to even notice it! It protects you from server side attacks.

Check our [homepage](https://www.krptn.dev/) for more information!

It is possible to easily integrate this with Django and Flask.

Here is a diagram on our model:

![Krptn Visual](https://www.krptn.dev/krptnDiagram.webp)
