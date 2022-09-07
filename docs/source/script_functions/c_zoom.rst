.. _c_zoom:

c_zoom
========================

.. code-block:: text

	c_zoom(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "c_zoom",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4979,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "1.1",
	                "1.1",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4980,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "1",
	                "1",
	                "EaseInQuart"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4981,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.4",
	                "1",
	                "1"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_scale`
* :ref:`cmp_scale`
