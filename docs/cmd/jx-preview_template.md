## jx-preview template

Displays the output of 'helmfile template' for the preview

***Aliases**: tmp*

### Usage

```
jx-preview template
```

### Synopsis

Display one or more preview environments.

### Examples

  # Display the preview template yaml on the console
  jx preview template

### Options

```
      --app string               Name of the app or repository
  -f, --file string              Preview helmfile.yaml path to use. If not specified it is discovered in preview/helmfile.yaml and created from a template if needed
      --helmfile-binary string   specifies the helmfile binary location to use. If not specified defaults to using the downloaded helmfile plugin
  -h, --help                     help for template
```

### SEE ALSO

* [jx-preview](jx-preview.md)	 - Preview commands

###### Auto generated by spf13/cobra on 25-Jun-2021