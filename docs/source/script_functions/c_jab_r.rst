.. _c_jab_r:

c_jab_r
========================

.. code-block:: text

	c_jab_r(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.15, 80, 0, EaseOutCubic)
	mnu_move(CID, false, 0.1, -80, 0, EaseInCubic)
	cmp_move(CID, 0.25, 0, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_jab_r",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4956,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.15",
	                "80",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4957,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.1",
	                "-80",
	                "0",
	                "EaseInCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4958,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "0.25",
	                "0",
	                "0"
	            ],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
