# Android Material Design Component
*A list of Android Material Design Components and how apps can use them.*
## Table of Contents

  1. [Material Design Components](#material-design-components)
  1. [Dialog](#dialog)
  1. [Picker](#picker)
  1. [Nav Drawer](#nav-drawer)
  1. [Right Drawer](#right-drawer)
  1. [Modal Bottom Sheet](#modal-bottom-sheet)
  1. [Floating Action Button (FAB)](#floating-action-button-fab)
  1. [Sub Menu](#sub-menu)
  1. [Menu](#menu)
  1. [Card](#card)
  1. [Raised Button](#raised-button)
  1. [Snackbar](#snackbar)
  1. [App Bar](#app-bar)
  1. [Refresh Indicator](#refresh-indicator)
  1. [Search Bar / Quick Entry](#search-bar--quick-entry)
  1. [Switch](#switch)
  1. [References](#references)

## Material Design Components


## Dialog
  
  <a name="dialog-description"></a><a name="dialog-description"></a>
  - [**Description**:](#dialog-description)
  
  <a name="dialog-screenshot"></a><a name="dialog-screenshot"></a>
  - [**Screenshot**:](#dialog-screenshot)
  
  <a name="dialog-code-example"></a><a name="dialog-code-example"></a>
  - [**Code Examples**:](#dialog-code-example)

**[:top: back to top](#table-of-contents)**
  

## Picker

  <a name="picker-description"></a><a name="picker-description"></a>
  - [**Description**:](#picker-description)
  
  <a name="picker-screenshot"></a><a name="picker-screenshot"></a>
  - [**Screenshot**:](#picker-screenshot)
  
  <a name="picker-code-example"></a><a name="picker-code-example"></a>
  - [**Code Examples**:](#picker-code-example)

**[:top: back to top](#table-of-contents)**

## Nav Drawer

  <a name="nav-drawer-description"></a><a name="nav-drawer-description"></a>
  - [**Description**:](#nav-drawer-description)
  
  <a name="nav-drawer-screenshot"></a><a name="nav-drawer-screenshot"></a>
  - [**Screenshot**:](#nav-drawer-screenshot)
  
  <a name="nav-drawer-code-example"></a><a name="nav-drawer-code-example"></a>
  - [**Code Examples**:](#nav-drawer-code-example)

**[:top: back to top](#table-of-contents)**

## Right Drawer

  <a name="right-drawer-description"></a><a name="right-drawer-description"></a>
  - [**Description**:](#right-drawer-description)
  
  <a name="right-drawer-screenshot"></a><a name="right-drawer-screenshot"></a>
  - [**Screenshot**:](#right-drawer-screenshot)
  
  <a name="right-drawer-code-example"></a><a name="right-drawer-code-example"></a>
  - [**Code Examples**:](#right-drawer-code-example)

**[:top: back to top](#table-of-contents)**

## Modal Bottom Sheet

  <a name="modal-bottom-sheet-description"></a><a name="modal-bottom-sheet-description"></a>
  - [**Description**:](#modal-bottom-sheet-description)
  
  <a name="modal-bottom-sheet-screenshot"></a><a name="modal-bottom-sheet-screenshot"></a>
  - [**Screenshot**:](#modal-bottom-sheet-screenshot)
  
  <a name="modal-bottom-sheet-code-example"></a><a name="modal-bottom-sheet-code-example"></a>
  - [**Code Examples**:](#modal-bottom-sheet-code-example)

**[:top: back to top](#table-of-contents)**

## Floating Action Button (FAB)

  <a name="fab-description"></a><a name="fab-description"></a>
  - [**Description**:](#fab-description)
  
  <a name="fab-screenshot"></a><a name="fab-screenshot"></a>
  - [**Screenshot**:](#fab-screenshot)
  
  ![FAB](images/fab.png)
  
  <a name="fab-code-example"></a><a name="fab-code-example"></a>
  - [**Code Examples**:](#fab-code-example)
  
  The FAB can be created using an ImageButton view and giving it a special __background__ image (Oval shape) and setting its __elevation__ to a desired depth.
   
   ```xml
<ImageButton
    android:layout_width="56dp"
    android:layout_height="56dp"
    android:layout_margin="20dp"
    android:background="@drawable/oval_ripple_shape"
    android:src="@drawable/fab_plus"
    android:elevation="6dp"
    android:stateListAnimator="@anim/fab_raise"/>
   ```
   drawable/oval\_ripple\_shape.xml
   
   ```xml
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="oval">
    <solid android:color="?attr/colorAccent"/>
</shape>
   ```
   OR
   
   ```xml
<ripple xmlns:android="http://schemas.android.com/apk/res/android"
        android:color="?android:colorControlHighlight"
        android:shape="oval">
  <item>
    <shape android:shape="oval">
      <solid android:color="?android:colorAccent"/>
    </shape>
  </item>
</ripple>
   ```
 
 

**[:top: back to top](#table-of-contents)**

## Sub Menu

  <a name="sub-menu-description"></a><a name="sub-menu-description"></a>
  - [**Description**:](#sub-menu-description)
  
  <a name="sub-menu-screenshot"></a><a name="sub-menu-screenshot"></a>
  - [**Screenshot**:](#sub-menu-screenshot)
  
  <a name="sub-menu-code-example"></a><a name="sub-menu-code-example"></a>
  - [**Code Examples**:](#sub-menu-code-example)

**[:top: back to top](#table-of-contents)**

## Menu

  <a name="menu-description"></a><a name="menu-description"></a>
  - [**Description**:](#menu-description)
  
  <a name="menu-screenshot"></a><a name="menu-screenshot"></a>
  - [**Screenshot**:](#menu-screenshot)
  
  <a name="menu-code-example"></a><a name="menu-code-example"></a>
  - [**Code Examples**:](#menu-code-example)

**[:top: back to top](#table-of-contents)**

## Card

  <a name="card-description"></a><a name="card-description"></a>
  - [**Description**:](#card-description)
  
  <a name="card-screenshot"></a><a name="card-screenshot"></a>
  - [**Screenshot**:](#card-screenshot)
  
  <a name="card-code-example"></a><a name="card-code-example"></a>
  - [**Code Examples**:](#card-code-example)

**[:top: back to top](#table-of-contents)**

## Raised Button

  <a name="raised-button-description"></a><a name="raised-button-description"></a>
  - [**Description**:](#raised-button-description)
  
  <a name="raised-button-screenshot"></a><a name="raised-button-screenshot"></a>
  - [**Screenshot**:](#raised-button-screenshot)
  
  <a name="raised-button-code-example"></a><a name="raised-button-code-example"></a>
  - [**Code Examples**:](#raised-button-code-example)

**[:top: back to top](#table-of-contents)**

## Snackbar

  <a name="snackbar-description"></a><a name="snackbar-description"></a>
  - [**Description**:](#snackbar-description)
  
  <a name="snackbar-screenshot"></a><a name="snackbar-screenshot"></a>
  - [**Screenshot**:](#snackbar-screenshot)
  
  <a name="snackbar-code-example"></a><a name="snackbar-code-example"></a>
  - [**Code Examples**:](#snackbar-code-example)

**[:top: back to top](#table-of-contents)**

## App Bar

  <a name="app-bar-description"></a><a name="app-bar-description"></a>
  - [**Description**:](#app-bar-description)
  
  <a name="app-bar-screenshot"></a><a name="app-bar-screenshot"></a>
  - [**Screenshot**:](#app-bar-screenshot)
  
  <a name="app-bar-code-example"></a><a name="app-bar-code-example"></a>
  - [**Code Examples**:](#app-bar-code-example)

**[:top: back to top](#table-of-contents)**

## Refresh Indicator

  <a name="refresh-indicator-description"></a><a name="refresh-indicator-description"></a>
  - [**Description**:](#refresh-indicator-description)
  
  <a name="refresh-indicator-screenshot"></a><a name="refresh-indicator-screenshot"></a>
  - [**Screenshot**:](#refresh-indicator-screenshot)
  
  <a name="refresh-indicator-code-example"></a><a name="refresh-indicator-code-example"></a>
  - [**Code Examples**:](#refresh-indicator-code-example)

**[:top: back to top](#table-of-contents)**

## Search Bar / Quick Entry

  <a name="search-bar-description"></a><a name="search-bar-description"></a>
  - [**Description**:](#search-bar-description)
  
  <a name="search-bar-screenshot"></a><a name="search-bar-screenshot"></a>
  - [**Screenshot**:](#search-bar-screenshot)
  
  <a name="search-bar-code-example"></a><a name="search-bar-code-example"></a>
  - [**Code Examples**:](#search-bar-code-example)

**[:top: back to top](#table-of-contents)**

## Switch

  <a name="switch-description"></a><a name="switch-description"></a>
  - [**Description**:](#switch-description)
  
  <a name="switch-screenshot"></a><a name="switch-screenshot"></a>
  - [**Screenshot**:](#switch-screenshot)
  
  <a name="switch-code-example"></a><a name="switch-code-example"></a>
  - [**Code Examples**:](#switch-code-example)

**[:top: back to top](#table-of-contents)**


## References

- [Google Design Guidelines, Material Design](http://www.google.com/design/spec)