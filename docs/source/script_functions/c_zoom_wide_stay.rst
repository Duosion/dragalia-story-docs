.. _c_zoom_wide_stay:

c_zoom_wide_stay
========================

.. code-block:: text

	c_zoom_wide_stay(CID)


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
	    "name": "c_zoom_wide_stay",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 5004,
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
	            "row": 5005,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.2",
	                "1.3",
	                "1.3"
	            ],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`mnu_scale`
* :ref:`cmp_scale`
