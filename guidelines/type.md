---
layout: template1
title: Type
data: type
comments: false
---

{% include guidelines.md %}

### Access Guidelines

**DPLA MAP v4 Usage:** Nature of genre of described resource. Vocab Schema: dcterms:DCMIType.

Type characterizes the nature of the resource and should be expressed as a term from the [DCMI Type](http://dublincore.org/documents/2012/06/14/dcmi-terms/?v=dcmitype#H7) vocabulary. **This field is non-repeatable. If a resource can be characterized by more than one term, choose the term best characterizes the resource or characterizes most of the resource.**

__Commonly Used Terms__
These are the most commonly used terms in our collections:

Term | Definition | Examples from DCMI Definition | Local Notes
-----|------------|------------------|------------
Text | A resource consisting primarily of words for reading. | Examples include books, letters, dissertations, poems, newspapers, articles, archives of mailing lists. Note that facsimiles or images of texts are still of the genre Text.| Use this for works that are chiefly textual in nature.
Image | A visual representation other than text. | Examples include images and photographs of physical objects, paintings, prints, drawings, other images and graphics, animations and moving pictures, film, diagrams, maps, musical notation. Note that Image may include both electronic and physical representations. | Use `Image` for all types of still images. We will **not** use `Still Image` in collections. `Image` has a broad application and is used by DPLA.
Moving Image | A series of visual representations imparting an impression of motion when shown in succession. | Examples include animations, movies, television programs, videos, zoetropes, or visual output from a simulation. Instances of the type Moving Image must also be describable as instances of the broader type Image. | Use for video recordings.
Sound | A resource primarily intended to be heard. | Examples include a music playback file format, an audio compact disc, and recorded speech or sounds. | Use for sound recordings.

### Preservation Guidelines

This field is not included in the preservation package.
