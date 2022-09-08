.. _c_zoom2_wide:

c_zoom2_wide
========================

.. code-block:: text

	c_zoom2_wide(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_scale(CID, true, 0.2, 1.3, 1.3, EaseOutCubic)
	mnu_scale(CID, false, 0.2, 1, 1, EaseInQuart)
	mnu_scale(CID, false, 0.2, 1.3, 1.3, EaseOutQuart)
	mnu_scale(CID, false, 0.2, 1, 1, EaseInQuart)
	cmp_scale(CID, 0.8, 1, 1)

References
-------------
* :ref:`mnu_scale`
* :ref:`cmp_scale`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_zoom2_wide",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4991,
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
	            "row": 4992,
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
	            "row": 4993,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "false",
	                "0.2",
	                "1.3",
	                "1.3",
	                "EaseOutQuart"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4994,
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
	            "row": 4995,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.8",
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
