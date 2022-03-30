# Backend useful resources

This repo contains examples, code snippets, meetup records and speeches
Collected resources is shared with all developers


## For publishing:
1. Highly recommended to make new push through PR's
2. Do not code with sensitive information, it is enough for all code snippets to have undestable example values
3. Approximate template for publishing must have hierarchy, which is described in the next section

## Sections

**Patterns** - for resources with patterns (from weekly meetups)
**Meetups** - for resources from individual meetups
**Django** - for resources with meetups/discource about Django
**Useful** - for resources with just interesting things, or if they do not fit in the previous sections


## File hierarchy template

Create directory as described:
```
name_of_resource/                    # Actual folder
name_of_resource/code                # contains examples of code
name_of_resource/presentation.pdf    # file of presentation (if exists), can be in PDF, PPTX, or other formats
name_of_resource/README.md           # Readme with description of resource, can be in free form
```

And put this directory `name_of_resource` to matching section.

For example:
```
Patterns/Singleton
Patterns/Singleton/code/singleton.py
Patterns/Singleton/presentation.pptx
Patterns/Singleton/README.md
```
