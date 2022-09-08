.. _event_still_set:

event_still_set
========================

.. code-block:: text

	event_still_set(Rayer, Sec, Rayer1, X1, Rayer2, X2, Rayer3, X3)


Arguments
------------

* Rayer
* Sec
* Rayer1
* X1
* Rayer2
* X2
* Rayer3
* X3

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: python

	if Rayer == 1:
		CHARA_SET_POS_0(M, M, X1, 0, Rayer1, 1)
		CHARA_UNCOLOR(Rayer1)
		mnu_fade(Rayer1, true, Sec, 1, EaseOutSine)
		cmp_fade(Rayer1, Sec, 1)
	elif Rayer == 2:
		CHARA_SET_POS_0(M, M, X1, 0, Rayer1, 1)
		CHARA_SET_POS_0(M, M, X2, 0, Rayer2, 1)
		CHARA_UNCOLOR(Rayer1)
		CHARA_UNCOLOR(Rayer2)
		mnu_fade(Rayer1, true, Sec, 1, EaseOutSine)
		mnu_fade(Rayer2, true, Sec, 1, EaseOutSine)
		cmp_fade(Rayer1, Sec, 1)
		cmp_fade(Rayer2, Sec, 1)
	elif Rayer == 3:
		CHARA_SET_POS_0(M, M, X1, 0, Rayer1, 1)
		CHARA_SET_POS_0(M, M, X2, 0, Rayer2, 1)
		CHARA_SET_POS_0(M, M, X3, 0, Rayer3, 1)
		CHARA_UNCOLOR(Rayer1)
		CHARA_UNCOLOR(Rayer2)
		CHARA_UNCOLOR(Rayer3)
		mnu_fade(Rayer1, true, Sec, 1, EaseOutSine)
		mnu_fade(Rayer2, true, Sec, 1, EaseOutSine)
		mnu_fade(Rayer3, true, Sec, 1, EaseOutSine)
		cmp_fade(Rayer1, Sec, 1)
		cmp_fade(Rayer2, Sec, 1)
		cmp_fade(Rayer3, Sec, 1)
	else:

References
-------------
* :ref:`CHARA_SET_POS_0`
* :ref:`CHARA_UNCOLOR`
* :ref:`mnu_fade`
* :ref:`cmp_fade`

Table Implementation
-------------

.. code-block:: json

	{
	    "name": "event_still_set",
	    "args": [
	        "Rayer",
	        "Sec",
	        "Rayer1",
	        "X1",
	        "Rayer2",
	        "X2",
	        "Rayer3",
	        "X3"
	    ],
	    "commandList": [
	        {
	            "row": 5472,
	            "command": "if",
	            "args": [
	                "Rayer",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5473,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "M",
	                "M",
	                "X1",
	                "0",
	                "Rayer1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5474,
	            "command": "CHARA_UNCOLOR",
	            "args": [
	                "Rayer1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5475,
	            "command": "mnu_fade",
	            "args": [
	                "Rayer1",
	                "true",
	                "Sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5476,
	            "command": "cmp_fade",
	            "args": [
	                "Rayer1",
	                "Sec",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5478,
	            "command": "elif",
	            "args": [
	                "Rayer",
	                "2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5479,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "M",
	                "M",
	                "X1",
	                "0",
	                "Rayer1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5480,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "M",
	                "M",
	                "X2",
	                "0",
	                "Rayer2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5481,
	            "command": "CHARA_UNCOLOR",
	            "args": [
	                "Rayer1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5482,
	            "command": "CHARA_UNCOLOR",
	            "args": [
	                "Rayer2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5483,
	            "command": "mnu_fade",
	            "args": [
	                "Rayer1",
	                "true",
	                "Sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5484,
	            "command": "mnu_fade",
	            "args": [
	                "Rayer2",
	                "true",
	                "Sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5485,
	            "command": "cmp_fade",
	            "args": [
	                "Rayer1",
	                "Sec",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5486,
	            "command": "cmp_fade",
	            "args": [
	                "Rayer2",
	                "Sec",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5488,
	            "command": "elif",
	            "args": [
	                "Rayer",
	                "3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5489,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "M",
	                "M",
	                "X1",
	                "0",
	                "Rayer1",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5490,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "M",
	                "M",
	                "X2",
	                "0",
	                "Rayer2",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5491,
	            "command": "CHARA_SET_POS_0",
	            "args": [
	                "M",
	                "M",
	                "X3",
	                "0",
	                "Rayer3",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5492,
	            "command": "CHARA_UNCOLOR",
	            "args": [
	                "Rayer1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5493,
	            "command": "CHARA_UNCOLOR",
	            "args": [
	                "Rayer2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5494,
	            "command": "CHARA_UNCOLOR",
	            "args": [
	                "Rayer3"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5495,
	            "command": "mnu_fade",
	            "args": [
	                "Rayer1",
	                "true",
	                "Sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5496,
	            "command": "mnu_fade",
	            "args": [
	                "Rayer2",
	                "true",
	                "Sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5497,
	            "command": "mnu_fade",
	            "args": [
	                "Rayer3",
	                "true",
	                "Sec",
	                "1",
	                "EaseOutSine"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5498,
	            "command": "cmp_fade",
	            "args": [
	                "Rayer1",
	                "Sec",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5499,
	            "command": "cmp_fade",
	            "args": [
	                "Rayer2",
	                "Sec",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5500,
	            "command": "cmp_fade",
	            "args": [
	                "Rayer3",
	                "Sec",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 5501,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 5502,
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
