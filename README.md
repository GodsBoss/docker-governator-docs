Governator docs (Docker)
========================

Dockerfile to create an image which runs the [Governator][governator] documentation, source is [governator.io][governator-io]. Formerly found at a domain with the same name, now unregistered.

Usage
-----

    docker run -d -p 37831:37831 godsboss/governator-docs

Then open [localhost:37831](http://localhost:37831) in your browser.

[governator]: https://github.com/rainycape/governator
[governator-io]: https://github.com/rainycape/governator.io
