.. _window:

window
========================

.. code-block:: text

	window(cmd)


Arguments
------------

* cmd

Description
-------------

Not Added.

Implementation
-------------

.. code-block:: json

	{
	    "name": "window",
	    "args": [
	        "cmd"
	    ],
	    "commandList": [
	        {
	            "row": 85,
	            "command": "if",
	            "args": [
	                "cmd",
	                "f_in"
	            ],
	            "end": 1
	        },
	        {
	            "row": 86,
	            "command": "window_fadein",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 87,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "f_out"
	            ],
	            "end": 1
	        },
	        {
	            "row": 88,
	            "command": "window_fadeout",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 89,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "f_in_s"
	            ],
	            "end": 1
	        },
	        {
	            "row": 90,
	            "command": "window_fadein",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 91,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "f_out_s"
	            ],
	            "end": 1
	        },
	        {
	            "row": 92,
	            "command": "window_fadeout",
	            "args": [
	                "0.2"
	            ],
	            "end": 1
	        },
	        {
	            "row": 93,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_in"
	            ],
	            "end": 1
	        },
	        {
	            "row": 94,
	            "command": "screen_fadein",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 95,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_in_vs"
	            ],
	            "end": 1
	        },
	        {
	            "row": 96,
	            "command": "screen_fadein",
	            "args": [
	                "0.2",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 97,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_in_md"
	            ],
	            "end": 1
	        },
	        {
	            "row": 98,
	            "command": "screen_fadein",
	            "args": [
	                "0.3",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 99,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_in_s"
	            ],
	            "end": 1
	        },
	        {
	            "row": 100,
	            "command": "screen_fadein",
	            "args": [
	                "0.4",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 101,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_in_l"
	            ],
	            "end": 1
	        },
	        {
	            "row": 102,
	            "command": "screen_fadein",
	            "args": [
	                "2.0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 103,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_in_vl"
	            ],
	            "end": 1
	        },
	        {
	            "row": 104,
	            "command": "screen_fadein",
	            "args": [
	                "4.0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 105,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "farst_int"
	            ],
	            "end": 1
	        },
	        {
	            "row": 106,
	            "command": "RESET_TEXT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 107,
	            "command": "window_fadeout",
	            "args": [
	                "0",
	                "true"
	            ],
	            "end": 1
	        },
	        {
	            "row": 108,
	            "command": "BGMFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 109,
	            "command": "SEFOUT_DEF",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 110,
	            "command": "screen_fadeout",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 111,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_out"
	            ],
	            "end": 1
	        },
	        {
	            "row": 112,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 113,
	            "command": "screen_fadeout",
	            "args": [
	                "1.0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 114,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_out_vs"
	            ],
	            "end": 1
	        },
	        {
	            "row": 115,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 116,
	            "command": "screen_fadeout",
	            "args": [
	                "0.3",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 117,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_out_ms"
	            ],
	            "end": 1
	        },
	        {
	            "row": 118,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 119,
	            "command": "screen_fadeout",
	            "args": [
	                "0.6",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 120,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_out_l"
	            ],
	            "end": 1
	        },
	        {
	            "row": 121,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 122,
	            "command": "screen_fadeout",
	            "args": [
	                "2.0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 123,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "bk_out_vl"
	            ],
	            "end": 1
	        },
	        {
	            "row": 124,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 125,
	            "command": "screen_fadeout",
	            "args": [
	                "4.0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 126,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_in_ms"
	            ],
	            "end": 1
	        },
	        {
	            "row": 127,
	            "command": "screen_fadein",
	            "args": [
	                "0.6",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 128,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_in"
	            ],
	            "end": 1
	        },
	        {
	            "row": 129,
	            "command": "screen_fadein",
	            "args": [
	                "1.0",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 130,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_in_l"
	            ],
	            "end": 1
	        },
	        {
	            "row": 131,
	            "command": "screen_fadein",
	            "args": [
	                "2.0",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 132,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_in_vl"
	            ],
	            "end": 1
	        },
	        {
	            "row": 133,
	            "command": "screen_fadein",
	            "args": [
	                "4.0",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 134,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_out_pr_l"
	            ],
	            "end": 1
	        },
	        {
	            "row": 135,
	            "command": "screen_fadeout",
	            "args": [
	                "2.1",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 136,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_out_pr_vs"
	            ],
	            "end": 1
	        },
	        {
	            "row": 137,
	            "command": "screen_fadeout",
	            "args": [
	                "0",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 138,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_out_ms"
	            ],
	            "end": 1
	        },
	        {
	            "row": 139,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 140,
	            "command": "screen_fadeout",
	            "args": [
	                "0.6",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 141,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_out"
	            ],
	            "end": 1
	        },
	        {
	            "row": 142,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 143,
	            "command": "screen_fadeout",
	            "args": [
	                "1.0",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 144,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_out_l"
	            ],
	            "end": 1
	        },
	        {
	            "row": 145,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 146,
	            "command": "screen_fadeout",
	            "args": [
	                "2.0",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 147,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "wt_out_vl"
	            ],
	            "end": 1
	        },
	        {
	            "row": 148,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 149,
	            "command": "screen_fadeout",
	            "args": [
	                "4.0",
	                "255",
	                "255",
	                "255"
	            ],
	            "end": 1
	        },
	        {
	            "row": 150,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "trns_in_r"
	            ],
	            "end": 1
	        },
	        {
	            "row": 151,
	            "command": "fade_color",
	            "args": [
	                "0.25",
	                "0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 152,
	            "command": "screen_transin",
	            "args": [
	                "1",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 153,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "trns_in_l"
	            ],
	            "end": 1
	        },
	        {
	            "row": 154,
	            "command": "fade_color",
	            "args": [
	                "0.25",
	                "0",
	                "0",
	                "0",
	                "0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 155,
	            "command": "screen_transin",
	            "args": [
	                "2",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 156,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "trns_out_r"
	            ],
	            "end": 1
	        },
	        {
	            "row": 157,
	            "command": "WFOUT_SHORT",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 158,
	            "command": "screen_transout",
	            "args": [
	                "2",
	                "1.0"
	            ],
	            "end": 1
	        },
	        {
	            "row": 159,
	            "command": "fade_color",
	            "args": [
	                "0.25",
	                "0",
	                "0",
	                "0",
	                "1"
	            ],
	            "end": 1
	        },
	        {
	            "row": 160,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "curtain"
	            ],
	            "end": 1
	        },
	        {
	            "row": 161,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_107"
	            ],
	            "end": 1
	        },
	        {
	            "row": 162,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "9"
	            ],
	            "end": 1
	        },
	        {
	            "row": 163,
	            "command": "elif",
	            "args": [
	                "cmd",
	                "curtaout"
	            ],
	            "end": 1
	        },
	        {
	            "row": 164,
	            "command": "set_BG_effect",
	            "args": [
	                "EFF_107"
	            ],
	            "end": 1
	        },
	        {
	            "row": 165,
	            "command": "set_BG_effect_trigger",
	            "args": [
	                "8"
	            ],
	            "end": 1
	        },
	        {
	            "row": 166,
	            "command": "wait",
	            "args": [
	                "0.5"
	            ],
	            "end": 1
	        },
	        {
	            "row": 167,
	            "command": "else",
	            "args": [],
	            "end": 1
	        },
	        {
	            "row": 168,
	            "command": "endif",
	            "args": [],
	            "end": 1
	        }
	    ]
	}

References
-------------
* :ref:`window_fadein`
* :ref:`window_fadeout`
* :ref:`screen_fadein`
* :ref:`RESET_TEXT`
* :ref:`BGMFOUT_DEF`
* :ref:`SEFOUT_DEF`
* :ref:`screen_fadeout`
* :ref:`WFOUT_SHORT`
* :ref:`fade_color`
* :ref:`screen_transin`
* :ref:`screen_transout`
* :ref:`set_BG_effect`
* :ref:`set_BG_effect_trigger`
* :ref:`wait`
