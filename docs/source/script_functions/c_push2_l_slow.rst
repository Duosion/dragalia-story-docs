.. _c_push2_l_slow:

c_push2_l_slow
========================

.. code-block:: text

	c_push2_l_slow(CID)


Arguments
------------

* CID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	mnu_move(CID, true, 0.2, 0, 0, EaseOutCubic)
	mnu_move(CID, false, 0.6, -50, 0, EaseOutCubic)
	mnu_move(CID, false, 0.5, 0, 0, EaseOutCubic)
	mnu_move(CID, false, 0.4, -50, 0, EaseOutCubic)
	cmp_move(CID, 1.7, -100, 0)

References
-------------
* :ref:`mnu_move`
* :ref:`cmp_move`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "c_push2_l_slow",
	    "args": [
	        "CID"
	    ],
	    "commandList": [
	        {
	            "row": 4633,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "true",
	                "0.2",
	                "0",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4634,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.6",
	                "-50",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4635,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.5",
	                "0",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4636,
	            "command": "mnu_move",
	            "args": [
	                "CID",
	                "false",
	                "0.4",
	                "-50",
	                "0",
	                "EaseOutCubic"
	            ],
	            "end": 1
	        },
	        {
	            "row": 4637,
	            "command": "cmp_move",
	            "args": [
	                "CID",
	                "1.7",
	                "-100",
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
