.. _Negaposi:

Negaposi
========================

.. code-block:: text

	Negaposi(SEC, CAMERA, R, G, B)


Arguments
------------

* SEC
* CAMERA
* R
* G
* B

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	bloom(CAMERA, SEC, -1, 0.0, -1, -1)
	color_adjustment(CAMERA, SEC, 1.0, 1.0, 1.0)
	post_film(CAMERA, SEC, filmMode_Lerp, 0.0, 1.57, R, G, B, 1.0)

References
-------------
* :ref:`bloom`
* :ref:`color_adjustment`
* :ref:`post_film`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "Negaposi",
	    "args": [
	        "SEC",
	        "CAMERA",
	        "R",
	        "G",
	        "B"
	    ],
	    "commandList": [
	        {
	            "row": 5131,
	            "command": "bloom",
	            "args": [
	                "CAMERA",
	                "SEC",
	                "-1",
	                "0.0",
	                "-1",
	                "-1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5132,
	            "command": "color_adjustment",
	            "args": [
	                "CAMERA",
	                "SEC",
	                "1.0",
	                "1.0",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5133,
	            "command": "post_film",
	            "args": [
	                "CAMERA",
	                "SEC",
	                "filmMode_Lerp",
	                "0.0",
	                "1.57",
	                "R",
	                "G",
	                "B",
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
