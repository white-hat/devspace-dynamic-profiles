## Dynamic profiles for devpace (idea)
Currently, in order to apply the same patches to multiple pods, a user has to create a new profile for
every pod and copy each patch. Instead, I suggest using a simple approach with profile templates, where a user can
specify a profile template once, and later reuse it multiple times, providing pod and contanier names as parameters

## Dynamic defaults for variables for devpace (idea)
Currently, `default` field for variables does not support variable expansion, which introduces extra complexity as user has to use an intermediate variable. I suggest allowing variable expanstion in `default` field
