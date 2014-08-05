sample.zosConnect
=================
This project contains the JCL procedures for creating the z/OS Connect data
transformation artifacts. Copy the JCL procedures from this location into
a JCL procedure library on your z/OS system.

The BBGLS2JS procedure generates a JSON schema and binding file from a
high-level language structure.

The BBGJS2LS procedure generates a high-level language data structure and
JSON binding from a JSON schema.

You will need to provide JCL to invoke the procedures with the required
input parameters to generate the binding and schema files.  Refer to the
reference documentation on the procedures for information on the input
parameters, and an example job to help you use the procedures.

# Notice

© Copyright IBM Corporation 2014.

# License

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
````