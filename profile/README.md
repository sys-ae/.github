<p align="center"><img src="https://raw.githubusercontent.com/sys-ae/.github/main/assets/fieldopt.svg" width="64" alt="FieldOpt logo"></p>

<h2 align="center">SAE: Systems Architecture Engineering</h2>

<p align="center">Operational tools for technical field work.<br>
Free and open source.</p>

<p align="center"><a href="https://fieldopt.dev"><b>fieldopt.dev</b></a> · <a href="https://demo.fieldopt.dev">Live demo</a> · <a href="https://github.com/sys-ae/fieldopt">Source</a></p>

<p align="center">
<img src="https://raw.githubusercontent.com/sys-ae/.github/main/assets/console.jpg" width="92%" alt="The FieldOpt dispatch console mid-day: technicians, jobs and the timeline">
</p>

FieldOpt is a dispatch console for field service teams. It assigns each job to a
qualified technician, routes their day, and tracks it live on a timeline and a
map. The whole system lives inside Postgres: PL/pgSQL holds the routing, the
simulation engine and every screen of the console, PostgREST serves those
functions over HTTP, and nginx serves the static files. The live demo runs the
same SQL in your browser, on Postgres compiled to WebAssembly.

- **[fieldopt](https://github.com/sys-ae/fieldopt)**: the dispatch console and
  its database (PL/pgSQL, AGPL-3.0).
- **[fieldopt.github.io](https://github.com/sys-ae/fieldopt.github.io)**: the
  fieldopt.dev site.
- **Enterprise:** installation, support, integrations and training at
  [contact@fieldopt.dev](mailto:contact@fieldopt.dev).
- **Contributing:** bug reports and ideas are welcome in the
  [issues](https://github.com/sys-ae/fieldopt/issues).
- **Status:** v0.0.9, early development.
