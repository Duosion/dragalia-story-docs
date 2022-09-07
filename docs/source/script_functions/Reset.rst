.. _Reset:

Reset
========================

.. code-block:: text

	Reset(SEC, CAMERA)


Arguments
------------

* SEC
* CAMERA

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "Reset",
	    "args": [
	        "SEC",
	        "CAMERA"
	    ],
	    "commandList": [
	        {
	            "row": 5112,
	            "command": "blur",
	            "args": [
	                "false",
	                "SEC",
	                "1.0",
	                "1.0",
	                "CAMERA"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5113,
	            "command": "bloom",
	            "args": [
	                "CAMERA",
	                "SEC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5114,
	            "command": "color_adjustment",
	            "args": [
	                "CAMERA",
	                "SEC"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5115,
	            "command": "post_film",
	            "args": [
	                "CAMERA",
	                "SEC",
	                "-1",
	                "-1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}

References
-------------
* :ref:`blur`
* :ref:`bloom`
* :ref:`color_adjustment`
* :ref:`post_film`
