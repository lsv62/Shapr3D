
Моделювання
============

Basic controls and access
-------------------------

Selecting geometry
~~~~~~~~~~~~~~~~~~

Basic selection
"""""""""""""""

.. glossary::

    Select a face, sketch, or edge
        Click/Tap once

    Select an entire body or connected sketch elements
            Double-click/tap

    Select multiple items, one by one 
        Press the Shift key and click each item/Tap without interruption

    Select all
        Ctrl-A/Long tap and drag
        
    Deselect all
        Click/Tap an empty area or Esc
        

Area Selection
""""""""""""""

.. glossary::

    Area Selection Left to right
        Select elements that are completely within the selection box
        
    Area Selection Right to left
        Select all elements that the selection box touches
        
    Filter the Selection
        Use Tab to cycle through the selection filters

Notable Points
~~~~~~~~~~~~~~

.. glossary::

    Endpoints
        in linear, arc, and spline-based sketch elements or edges of bodies. 

    Midpoints
        middle point between two endpoints of a line segment. 

    Center points
        at the center of arc and circular edges, and planar rectangular faces. 

    Intersection points
        at which two lines meet or intersect. 

Accessing tools
~~~~~~~~~~~~~~~

.. glossary::

    Accessing tools
        * Menus 
        * Project Sidebar
        * Adaptive user interface
        * Modes 
        * Items Manager 
        * Keyboard shortcuts
        * Command Search 
        * Context menus
        * Menu Bars

Using the gizmo
~~~~~~~~~~~~~~~

GIZMO CENTER
""""""""""""

.. glossary::

    gizmo center functions:
        * defines the center of any rotational movement
        * controls the orientation of the gizmo

ARROWS
""""""""

.. glossary::

    Gizmo arrows
        provide linear and rotational controls

TILES
""""""""

.. glossary::

    Gizmo tiles
        dragged for linear movements along a plane

Sketch Controls
---------------

States of sketch points
~~~~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Sketch points states of constraints
        * Unconnected - points are free to move in any way within the sketch
        * Connected to another sketch point - points will move together when modified
        * Connected to a line or curve - can move along the line or curve or along a projection 
          of the line or curve
        * Connected to the center of a line - remain at the line's center if the line's length 
          or position is modified
        * Locked - fixed and cannot be moved

Sketch pattern constraint
~~~~~~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Sketch pattern
        created using the Pattern tool for sketch elements or sketch profiles

Editing sketch dimensions
~~~~~~~~~~~~~~~~~~~~~~~~~

DIMENSION TYPES
"""""""""""""""

.. glossary::

    Length/Absolute 
        Distance between the two endpoints of a line

    Length/Horizontal 
        Distance between the two line endpoints relative to the horizontal axis

    Length/Vertical 
        Distance between two line endpoints relative to the vertical axis

Defining your sketch plane
~~~~~~~~~~~~~~~~~~~~~~~~~~

Define a sketch plane:

* By selecting a plane before you start sketching
* By selecting a planar face or construction plane
* From the Orientation cube 
* From Views in Views and Appearance

To select a sketch tool right away press the Space bar after selecting a sketch tool and
draging your pointer to hover over the rectangle corresponding to the plane you’d like to sketch.

Changing a sketch plane
~~~~~~~~~~~~~~~~~~~~~~~

Move your sketch along the planes:

* Double-click/tap the Orientation Cube to set the view to default.
* Select Move/Rotate.
* Drag the tiles in the gizmo center to move your sketch along the planes.

Project spaces
-------------------

Modeling
~~~~~~~~~~~~~

.. glossary::

    Modeling space
        main working area when creating 2D sketches and 3D models

Visualization
~~~~~~~~~~~~~

.. glossary::

    Visualization
        renders model with materials, environment, and camera and depth

2D Drawing
~~~~~~~~~~~~~~~~

Add a 2D drawing
""""""""""""""""""

.. glossary::

    2D Drawings
        space to create 2D technical drawings

    Drawing Preferences dialog
        * Drawing Title
        * Sheet Size
        * Orientation
        * View-to-Sheet Scale
        * Include 4 Views

    Drawing Properties
        * Sheet
            * Orientation
            * Sheet Size
            * View Scale
            * Projection
            * Title Block
        * Dimensions
            * Units
            * Angle Format
            * Length Precision
            * Angle Precision
            * Decimal Separator
        * Line Widths
            * Visible Outlines
            * Hidden Lines
            * Dimension Lines
            * Center Lines
            * Section Lines
            * Detail Marks

Title block layouts
""""""""""""""""""""""

    Title Block Properties
        * Simple - default layout
        * Empty Sheet
        * Border Only
        * Horizontal
        * Vertical
        * Block
        * Block with Table - with an additional customize Table
         
Views
""""""""""

.. glossary::

    Base View
        the main building block used to create base, isometric and projection views 

    Section View
        canbe created from base or projection views 

    Detail View
        add detail views to your 2D Drawings 

Dimensions
""""""""""""

.. glossary::

    Dimensioning tool
        * Line Length
        * Point-to-Point Distance
        * Point-to-Line Distance
        * Line-to-Line Distance
        * Arc Angle
        * 3-Point Angle
        * Line-to-Line Angle
        * Radius
        * Diameter
        * Min-Max Distance

    Dimension editor badge 
        * Prefix Text
        * Tolerances
        * Suffix Text

Geometries
""""""""""""

.. glossary::

    Geometry types
        * Centerline
            * 2-Point Centerline
            * 2-Line Centerline
            * 3-Point Circular Centerline
            * 3-Point Centerline
        * Center mark - indicatiopn of the centers of circles, arcs, and circular edges
        * Intersection mark -mark points as references for dimensioning.

Note
""""""""""

.. glossary::

    Note
        annotate parts of drawing 

Image
""""""""

.. glossary::

    Image
        add images to your 2D Drawings

Sketch Menu
-----------

Automatic Line/Arc
~~~~~~~~~~~~~~~~~~

.. glossary::

    Line/Arc
        a feature specific to using a pen to sketch to a line or arc depending on your pen gesture.

    Start automatic Line/Arc sketching
        * Define your sketch plane
        * Start drawing a line or arc

Line
~~~~~~~~~

.. glossary::

    Line 
        * define sketch plane
        * select Line
        * click to add an endpoint
        * drag pointer to construct line

Arc
~~~~~~

.. glossary::

    Arc 
        create arcs

Spline
~~~~~~~~~

.. glossary::

    Spline 
        creates a polynomial curve

FIT POINT SPLINE
"""""""""""""""""""

.. glossary::

    Fit Point Spline
        create a curve by marking the specific location through which the curve should pass

CONTROL POINT SPLINES
""""""""""""""""""""""""""

.. glossary::

    Control Point Splines
        draw and shape a curve indirectly to gives more control over the full curve’s smoothness

Rectangle
~~~~~~~~~~~~~

.. glossary::

    Rectangle 
        * Center rectangle
        * Diagonal rectangle
        * Three-point rectangle

Circle
~~~~~~~

.. glossary::

    Circle 
        creates a closed sketch profile with a constant radius

Ellipse
~~~~~~~~~~~

.. glossary::

    Ellipse 
        creates a closed sketch profile that is defined by a major and minor axis

Polygon
~~~~~~~~~~~

.. glossary::

    Polygon
        * Triangle 
        * Pentagon 
        * Hexagon 
        * Octagon

Offset Edge (Sketch)
~~~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Offset Edge
        * Loop 
        * Single 

Move/Rotate (Sketch)
~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Move/Rotate 
        move or rotate sketch elements

Pattern (Sketch)
~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Pattern
        creates linear or circulR patterns of sketch elements to create 
        multiple copies of selected elements

    Pattern control badges
        * Pattern Definition
            * Total Distance [Total]
            * Spacing Distance [Spacing]
        * Quantity
        * Circular Orientation
            * Uniform
            * Rotated

Text
~~~~~~~~

.. glossary::

    Text
        add text to a default plane, a face, or a construction plane and use
        in the same way as any other sketch.

Project - Sketches
~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Project - Sketches 
        cast faces or edges of bodies as a reference to connect your sketch to a sketch plane
        
Constraints Menu
----------------

Constraints overview
~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Constraints 
        add information to your sketches that control their behavior when they are modified

Constraint Settings
~~~~~~~~~~~~~~~~~~~

AUTO-CONSTRAINING
"""""""""""""""""

.. glossary::

    Auto-constraining
        include Horizontal/Vertical, Perpendicular, Tangent (when an arc is created at an endpoint),
        and Coincident

CONSTRAINT & LOCKED DIMENSION VISIBILITY
""""""""""""""""""""""""""""""""""""""""

.. glossary::

    Constraint & Locked Dimension Visibility
        * Always Show Constraints
        * Always Show Dimensions

Adding and removing constraints
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

ADDING CONSTRAINTS
""""""""""""""""""

.. glossary::

    Add constraints 
        * The constraints menu
        * keyboard shortcuts by shift and letter
        * Drag and drop to connected point, coincident, midpoint
        * lock

    Schetch constraints
        * Parallel - sets parallel relationship between sketch line elements
        * Perpendicular - sets a right angle (90°) between elements
        * Tangent -  create a tangent relationship between sketch elements
        * Coincident - make sketch endpoints coincident with other elements
        * Midpoint - connect an endpoint with the center of a line
        * Concentric - create a concentric relationship between sketch arc elements
        * Horizontal/Vertical - create a horizontal or vertical relationship between linear sketch elements
        * Equal - creates an equal length for selected lines and an equal radius for selected arcs and circles
        * Symmetry - lie on opposite sides of an axis of symmetry
        * Disconnect - break the connection between connected points
        * Lock/Unlock - fixes a selected sketch element in its current position
        * Make construction -convert your sketch elements into construction geometry

Add Menu
--------

Understanding construction geometry
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Construction geometry
        * Construction planes
        * Construction axes
        * Construction sketch elements
        * construction line

Construction Axis
~~~~~~~~~~~~~~~~~

.. glossary::

    Create Construction Axis for
        * a circular pattern
        * a reference point or snapping point
        * a virtual intersection at a filleted corner

CREATING A CONSTRUCTION AXIS
""""""""""""""""""""""""""""

.. glossary::

    Create a Construction Axis
        Add > Construction Axis

CONSTRUCTION AXIS TYPES
"""""""""""""""""""""""

.. glossary::

    Construction Axis Between 2 points
        between sketch points and vertices, or a new point

    Construction Axis 2-Plane Intersection
        intersection of two selected planes, faces, or closed sketches

    Construction Axis Cylindrical/Conical
        at the center of a cylindrical or conical face

    Construction Axis Along edge
        at a selected linear edge of a body or a sketch line

    Construction Axis Perpendicular to Face
        perpendicular to a selected planar element and through a selected point

Construction Plane
~~~~~~~~~~~~~~~~~~

.. glossary::

    Construction Plane use for  
        * at the desired location for a new sketch.
        * as a mirroring plane.
        * for splitting bodies or making sectioned views.

CREATING A CONSTRUCTION PLANE
"""""""""""""""""""""""""""""

.. glossary::

    Creating construction plane
        Add > Construction Plane

CONSTRUCTION PLANE TYPES
""""""""""""""""""""""""

.. glossary::

    Construction plane Offset
        offset from an existing planar element

    Construction plane Midplane
        centered between two selected planar elements

    Construction plane 3 Points
        defined by three selected points

    Construction plane On Curve at Point
        normal to a curve at a selected point

    Construction plane Perpendicular to Edge
        perpendicular to a linear element located at a selected point

    Construction plane Along Edge at Angle
        rotated about a selected linear element

    Construction plane Parallel to Face
        offset from an existing planar element and located at a selected poin


Режими
------

Ізолювати
~~~~~~~~~~~~

.. glossary::

    Інструмент «Ізолювати»
        ізолює елемент моделі, щоб легко працювати над певними частинами чи
        тілами, не відволікаючись.

    Ізолювати елемент:
        * Виберіть елемент або елементи, які потрібно ізолювати.
        * З адаптивних режимів виберіть «Ізолювати», щоб увімкнути його

Розріз
~~~~~~~~~~~~

.. glossary::

    Інструмент "Розріз" 
        показує внутрішні частини тривимірних тіл, щоб переглянути та 
        змінити внутрішні частини вашої моделі

    Створити Розріз:
        * Виберіть площину
        * виберіть "Розріз", щоб увімкнути перегляд розрізу

Виміряти
~~~~~~~~~

.. glossary::

    Переглянути вимірювання:
        * виберіть «Виміряти», щоб відкрити спливаючу панель
        * виберіть елементи моделі, які ви хочете виміряти
 
    Закріпити вимірювання:
        * виберіть значок шпильки біля вимірювання
        * виберіть видалити біля закріпленого вимірювання

    Додати вимірювання точка-точка:
        * виберіть вимірювання між двома точками
        * виберіть тип вимірювання:
            * відстань від точки до точки
            * 3-точковий кут
        * виберіть поверхню, щоб знайти помічені точки
        * виберіть помічені точки, які ви хочете виміряти
        * виберіть Готово
