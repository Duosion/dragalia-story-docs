.. _c_zoom_stay:

c_zoom_stay
========================

.. code-block:: text

	c_zoom_stay(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_scale(CID, true, 0.2, 1.1, 1.1, EaseOutCubic)
	cmp_scale(CID, 0.2, 1.1, 1.1)

References
-------------
* :ref:`mnu_scale`
* :ref:`cmp_scale`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_zoom_stay",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4999,
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
	            "row": 5000,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.2",
	                "1.1",
	                "1.1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
