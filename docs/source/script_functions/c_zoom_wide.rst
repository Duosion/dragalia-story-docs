.. _c_zoom_wide:

c_zoom_wide
========================

.. code-block:: text

	c_zoom_wide(CID)


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
	    "name": "c_zoom_wide",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4985,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "1.3",
	                "1.3",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4986,
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
	            "row": 4987,
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
