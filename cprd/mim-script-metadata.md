# Minimum Information Model for CPRD script metadata

**Status**: Rough draft

This profile follows the 
[Minim model for defining checklists](https://github.com/wf4ever/ro-manager/blob/master/Minim/Minim-description.md) 
concepts texually, but is not yet formally specified in RDF. 

Scripts in a [CPRD research object](../)

A defines a [Checklist](https://github.com/wf4ever/ro-manager/blob/master/Minim/minim-revised.md#minimchecklist) with the constraints for a given *purpose*, 
expressed via a *model*. 

The [Model](https://github.com/wf4ever/ro-manager/blob/master/Minim/minim-revised.md#minimmodel) lists **requirements** to be satisfied, which are split according to the 
[RFC 2119](https://www.ietf.org/rfc/rfc2119) keywords MUST, SHOLD and MAY:

> **MUST**   This word, or the terms "REQUIRED" or "SHALL", mean that the
> definition is an absolute requirement of the specification.

> **SHOULD**   This word, or the adjective "RECOMMENDED", mean that there
> may exist valid reasons in particular circumstances to ignore a
> particular item, but the full implications must be understood and
> carefully weighed before choosing a different course.

> **MAY**   This word, or the adjective "OPTIONAL", mean that an item is
> truly optional.  One vendor may choose to include the item because a
> particular marketplace requires it or because the vendor feels that
> it enhances the product while another vendor may omit the same item.
> An implementation which does not include a particular option MUST be
> prepared to interoperate with another implementation which does
> include the option, though perhaps with reduced functionality. In the
> same vein an implementation which does include a particular option
> MUST be prepared to interoperate with another implementation which
> does not include the option (except, of course, for the feature the
> option provides.)

A [requirement](https://github.com/wf4ever/ro-manager/blob/master/Minim/minim-revised.md#minimrequirement) can be satisfied by implementing a **rule**, which can be a 
[QueryTestRule](https://github.com/wf4ever/ro-manager/blob/master/Minim/minim-revised.md#minimquerytestrule) to test the annotations metadata, or a 
**SoftwareEnvRule**.

The `QueryTestRule` can be broken down into an existence test ([CardinalityTest](https://github.com/wf4ever/ro-manager/blob/master/Minim/minim-revised.md#minimcardinalitytest-existence-test)) or liveness test ([AccessibilityTest](https://github.com/wf4ever/ro-manager/blob/master/Minim/minim-revised.md#minimaccessibilitytest-liveness-test)). For Research Object there is additionally an [AggregationTest](https://github.com/wf4ever/ro-manager/blob/master/Minim/minim-revised.md#minimaggregationtest)  to define what kind of resources must be aggregated in a Research Object.



## CPRD script model

Below these requirements for CPRD are expressed in human-readable forms.


### MUST requirements

* _e.g. The Research Object MUST have at least one resource that is a `ex:Script`._


### SHOULD requirements


### MAY requirements

