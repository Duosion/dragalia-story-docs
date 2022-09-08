.. _c_shrink_stay:

c_shrink_stay
========================

.. code-block:: text

	c_shrink_stay(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	def c_shrink_stay(CID):
		mnu_scale(CID, true, 0.2, 0.9, 0.9, EaseOutCubic)
		cmp_scale(CID, 0.2, 0.9, 0.9)

References
-------------
* :ref:`mnu_scale`
* :ref:`cmp_scale`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_shrink_stay",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4968,
	            "command": "mnu_scale",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0.9",
	                "0.9",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4969,
	            "command": "cmp_scale",
	            "args": [
	                "CID",
	                "0.2",
	                "0.9",
	                "0.9"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
