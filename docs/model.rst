.. _model:

model
=============
TODO Add Info.

--------------------------------------------------------------------------------

.. _model-functions:

Functions
----------------------
These functions are available as a static methods of the Folder class. It is not necessary to create an
instance in order to call them.

.. _model-getRepository:

getRepository(e)
********
``W.model.getRepository(e)``

=======  ==========================================================================================
``e``    ??. Needs Info.
=======  ==========================================================================================

Returns something.

--------------------------------------------------------------------------------

.. _model-properties:

Model properties
------------------------
These properties are available for the model objects.

================= ========= ==============================================================================================
``absoluteURI``   String    The full path name for the referenced folder in URI notation. Read only.
``alias``         Boolean   When true, the object refers to a file system alias or shortcut. Read only.
``created``       Date      The creation date of the referenced folder, or null if the object does not
                            refer to a folder on disk. Read only.
``displayName``   String    The localized name of the referenced folder, without the path. Read only.
``parent``        Folder    The Folder object for the folder that contains this folder, or ``null`` if this
                            object refers to the root folder of a volume. Read only.
================= ========= ==============================================================================================


