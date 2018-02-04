# Visible

VRML PROTO (based on `Switch`) that simplifies showing/hiding objects using a `SFBool` (whereas `Switch` uses a `SFInt32`).

	EXTERNPROTO Visible [
		exposedField  SFBool  visible   TRUE
		exposedField  MFNode  children  []
	] "proto.Visible.wrl#Visible"


-------------------------------------------------------------------------------

## Property `visible`

Sets the **visibility**:
 - when `TRUE`, the objects are shown
 - when `FALSE`, the objects are hidden.

Definition:
 - Field Type: `exposedField`
 - Data Type: `SFBool`
 - Default Value: `TRUE`


-------------------------------------------------------------------------------

## Property `children`

List of **nodes to show/hide**.

Definition:
 - Field Type: `exposedField`
 - Data Type: `MFNode`
 - Default Value: `[]`


-------------------------------------------------------------------------------

