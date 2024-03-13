
Моделювання
============

Основні елементи керування та доступу
--------------------------------------

Вибір геометрії
~~~~~~~~~~~~~~~~~~

Базовий вибір
"""""""""""""""

.. glossary::

    Базовий вибір
        * виберіть грань, ескіз або край - клікніть один раз
        * виберіть ціле тіло або з’єднані елементи ескізу – двічі клікніть
        * виберіть кілька елементів, один за іншим - натисніть Shift і клікніть кожен елемент
        * вибрати все - Ctrl-A
        * скасувати вибір усіх - клікніть порожню область або Esc

Вибір області
""""""""""""""

.. glossary::

    Вибір області
        * виділення області зліва направо - вибір елементів, які повністю знаходяться в полі виділення
        * виділення області справа наліво - вибір усіх елементів, яких торкається поле виділення
        * відфільтрувати виділення - використовуйте Tab для циклічного переходу між фільтрами вибору

Точки прив'язки
~~~~~~~~~~~~~~~~~

.. glossary::

    Точки прив'язки
        * кінцеві точки - в лінійних, дугових і сплайнових ескізних елементах або ребрах тіл
        * середини - середина між двома кінцями відрізка
        * центрові точки - в центрі дуг і кругових ребер, а також плоских прямокутних граней
        * точки перетину - в яких зустрічаються або перетинаються дві лінії

Використання gizmo
~~~~~~~~~~~~~~~~~~~~~~

.. glossary::

    Використання gizmo
        * центр gizmo:
            * визначає центр будь-якого обертального руху
            * контролює орієнтацію gizmo
        * стрілки gizmo - забезпечують лінійне та поворотне управління
        * плитки gizmo - перетягуються для лінійних переміщень уздовж площини

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
