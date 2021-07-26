.. _Config:

Config
=============
Tells the configuration.

--------------------------------------------------------------------------------

.. _config-properties:

Config properties
------------------------
These properties are available for Config.

================= ========= ==============================================================================================
``absoluteURI``   String    The full path name for the referenced folder in URI notation. Read only.
``alias``         Boolean   When true, the object refers to a file system alias or shortcut. Read only.
``created``       Date      The creation date of the referenced folder, or null if the object does not
                            refer to a folder on disk. Read only.
``displayName``   String    The localized name of the referenced folder, without the path. Read only.
``error``         String    A message describing the most recent file system error; see :ref:`file-access-error-messages`.
                            Typically set by the file system, but a script
                            can set it. Setting this value clears any error message and resets the error
                            bit for opened files. Contains the empty string if there is no error.
``exists``        Boolean   When true, this object refers to a folder that currently exists in the file
                            system. Read only.
``fsName``        String    The platform-specific name of the referenced folder as a full path name.
                            Read only.
``fullName``      String    The full path name for the referenced folder in URI notation. Read only.
``localizedName`` String    A localized version of the folder name portion of the absolute URI for the
                            referenced file, without the path specification. Read only.
``modified``      Date      The date of the referenced folder's last modification, or ``null`` if the object
                            does not refer to a folder on disk. Read only.
``name``          String    The folder name portion of the absolute URI for the referenced file,
                            without the path specification. Read only.
``parent``        Folder    The Folder object for the folder that contains this folder, or ``null`` if this
                            object refers to the root folder of a volume. Read only.
``path``          String    The path portion of the absolute URI for the referenced folder, without the
                            folder name. Read only.
``relativeURI``   String    The path name for the referenced folder in URI notation, relative to the
                            current folder. Read only.
================= ========= ==============================================================================================
