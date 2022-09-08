.. _c_zoom_short:

c_zoom_short
========================

.. code-block:: text

	c_zoom_short(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_zoom_short(CID):
		mnu_scale(CID, true, 0.15, 1.1, 1.1, EaseOutCubic)
		mnu_scale(CID, false, 0.15, 1, 1, EaseInQuart)
		cmp_scale(CID, 0.3, 1, 1)

References
-------------
* :ref:`mnu_scale`
* :ref:`cmp_scale`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_zoom_short",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4973,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "true",
	                "0.15",
	                "1.1",
	                "1.1",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4974,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "false",
	                "0.15",
	                "1",
	                "1",
	                "EaseInQuart"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4975,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.3",
	                "1",
	                "1"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
