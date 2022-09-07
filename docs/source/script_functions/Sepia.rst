.. _Sepia:

Sepia
========================

.. code-block:: text

	Sepia(SEC, CAMERA)


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
	    "name": "Sepia",
	    "args": [
	        "SEC",
	        "CAMERA"
	    ],
	    "commandList": [
	        {
	            "row": 5125,
	            "command": "bloom",
	            "args": [
	                "CAMERA",
	                "SEC",
	                "-1",
	                "0.8",
	                "-1",
	                "-1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5126,
	            "command": "color_adjustment",
	            "args": [
	                "CAMERA",
	                "SEC",
	                "1.0",
	                "0.0",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5127,
	            "command": "post_film",
	            "args": [
	                "CAMERA",
	                "SEC",
	                "filmMode_Mul",
	                "1.0",
	                "1.57",
	                "118",
	                "96",
	                "80",
	                "1.0"
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
* :ref:`bloom`
* :ref:`color_adjustment`
* :ref:`post_film`
