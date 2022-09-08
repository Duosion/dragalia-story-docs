.. _SET_BG:

SET_BG
========================

.. code-block:: text

	SET_BG(BGID)


Arguments
------------

* BGID

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	set_BG(BGID)
	if BGID == sty_bg_0031_100:
		bg_pos_x(60)
	elif BGID == sty_bg_0004_100:
		bg_pos_x(45)
	elif BGID == sty_bg_0033_101:
		bg_pos_x(10)
	elif BGID == sty_bg_0002_100:
		bg_pos_x(75)
	elif BGID == sty_bg_0003_100:
		bg_pos_x(40)
	elif BGID == sty_bg_0016_103:
		bg_pos_x(68)
	elif BGID == sty_bg_0049_100:
		bg_pos_x(-68)
	elif BGID == sty_bg_0049_101:
		bg_pos_x(-68)

References
-------------
* :ref:`set_BG`
* :ref:`bg_pos_x`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "SET_BG",
	    "args": [
	        "BGID"
	    ],
	    "commandList": [
	        {
	            "row": 3,
	            "command": "set_BG",
	            "args": [
	                "BGID"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5,
	            "command": "if",
	            "args": [
	                "BGID",
	                "sty_bg_0031_100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 6,
	            "command": "bg_pos_x",
	            "args": [
	                "60"
	            ],
	            "end": 1
	        },
	        {
	            "row": 7,
	            "command": "elif",
	            "args": [
	                "BGID",
	                "sty_bg_0004_100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 8,
	            "command": "bg_pos_x",
	            "args": [
	                "45"
	            ],
	            "end": 1
	        },
	        {
	            "row": 9,
	            "command": "elif",
	            "args": [
	                "BGID",
	                "sty_bg_0033_101"
	            ],
	            "end": 1
	        },
	        {
	            "row": 10,
	            "command": "bg_pos_x",
	            "args": [
	                "10"
	            ],
	            "end": 1
	        },
	        {
	            "row": 11,
	            "command": "elif",
	            "args": [
	                "BGID",
	                "sty_bg_0002_100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 12,
	            "command": "bg_pos_x",
	            "args": [
	                "75"
	            ],
	            "end": 1
	        },
	        {
	            "row": 13,
	            "command": "elif",
	            "args": [
	                "BGID",
	                "sty_bg_0003_100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 14,
	            "command": "bg_pos_x",
	            "args": [
	                "40"
	            ],
	            "end": 1
	        },
	        {
	            "row": 15,
	            "command": "elif",
	            "args": [
	                "BGID",
	                "sty_bg_0016_103"
	            ],
	            "end": 1
	        },
	        {
	            "row": 16,
	            "command": "bg_pos_x",
	            "args": [
	                "68"
	            ],
	            "end": 1
	        },
	        {
	            "row": 17,
	            "command": "elif",
	            "args": [
	                "BGID",
	                "sty_bg_0049_100"
	            ],
	            "end": 1
	        },
	        {
	            "row": 18,
	            "command": "bg_pos_x",
	            "args": [
	                "-68"
	            ],
	            "end": 1
	        },
	        {
	            "row": 19,
	            "command": "elif",
	            "args": [
	                "BGID",
	                "sty_bg_0049_101"
	            ],
	            "end": 1
	        },
	        {
	            "row": 20,
	            "command": "bg_pos_x",
	            "args": [
	                "-68"
	            ],
	            "end": 1
	        },
	        {
	            "row": 21,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

Sample
-------------

.. code-block:: json

	{}
