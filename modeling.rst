
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
