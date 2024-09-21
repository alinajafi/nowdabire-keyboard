# nowdabire-keyboard
Customized keyboard layouts for English and Persian

--- Unity, GNOME 3+, Cinnamon, KDE

To add Nowdabira keyboard layouts to the system, extract the tar.gz file, open a Terminal (with Ctrl+Alt+T) and run:
	cd /path/to/the/extracted/folder/
	sudo cp nd /usr/share/X11/xkb/symbols
	sudo cp evdev.xml /usr/share/X11/xkb/rules

On Ubuntu, to add Nd icons to the indicators, just copy icons content to ~/.icons/, or better yet to run:
	sudo cp -r icons/* /usr/share/icons/
	sudo rm /usr/share/icons/ubuntu-mono-{dark,light}/icon-theme.cache

If you had installed older versions of Nowdabire keyboard before, you may need to update the keyboard
layout configuration to make changes take effect:
	sudo dpkg-reconfigure xkb-data

--- GNOME 2, MATE

Extract the tar.gz file, open a Terminal (with Ctrl+Alt+T) and run:
	cd /path/to/the/extracted/folder/
	sudo cp {nd,MATE/ir} /usr/share/X11/xkb/symbols
	sudo cp MATE/evdev.xml /usr/share/X11/xkb/rules


Then, you can select any layout; Nowdabire, Nowdabire Optimal, Nowdabire (US), or/and Persian Superstandard:

=====================================Layouts=================================================================

(Level 4) Right Alt + Shift
(Level 3) Right Alt
(Level 2) Shift
(Level 1) -

=====================================Nowdabire 8.0 - Ordibeheŝt e ’96========================================
										Ø	≠	±
	¹	²	³	£	€	÷	×	•	LRM	°	–	−
~	!	@	#	$	%	^	&	*	(	)	_	+
`	1	2	3	4	5	6	7	8	9	0	-	=
-------------------------------------------------------------------------------------------------------------
											{	}	|
			É				Ú	Í	Ó		[	]	\
													
	Q	W	E	R	T	Y	U	I	O	P	Ŝ	Ĵ	Ë
-------------------------------------------------------------------------------------------------------------
								«	»		‘
	Á	Ś			Ĝ			“	”	Ã	’
											"
	A	S	D	F	G	H	J	K	L	Â	'
-------------------------------------------------------------------------------------------------------------
								≤	≥	·
¦	Ź		Ɛ	Ʌ	CAA		µ	<	>	…
|								;	:	?
\	Z	X	C	V	B	N	M	,	.	/
-------------------------------------------------------------------------------------------------------------

					No-Break Space

					Space
=============================================================================================================
LRM: Left-to-Right Mark
CAA: Combining Acute Accent, to insert acute on an arbitrary letter, for example: ʌ́.


=====================================Nowdabire (US) 4.0 - Ordibeheŝt e ’96===================================
										Ø	≠	±
	¹	²	³	£	€	÷	×	•	LRM	°	–	−
~	!	@	#	$	%	^	&	*	(	)	_	+
`	1	2	3	4	5	6	7	8	9	0	-	=
-------------------------------------------------------------------------------------------------------------
													
			Ë	É	Á	Ã	Ú	Í	Ó				
											{	}	|
	Q	W	E	R	T	Y	U	I	O	P	[	]	\
-------------------------------------------------------------------------------------------------------------
								«	»	′	″
	Â	Ŝ					Ĵ	“	”	‘	’
										;	"
	A	S	D	F	G	H	J	K	L	:	'
-------------------------------------------------------------------------------------------------------------
								≤	≥	·
	Ź	Ś	Ɛ	Ʌ	CAA		µ		…	
								<	>	?
	Z	X	C	V	B	N	M	,	.	/
-------------------------------------------------------------------------------------------------------------

					No-Break Space

					Space
=============================================================================================================
LRM: Left-to-Right Mark
CAA: Combining Acute Accent, to insert acute on an arbitrary letter, for example: ʌ́.


=====================================Persian (Superstandard) 5.0 - Ŝahrivar e ’91============================
‎	1	2	3	4	5	6	7	8	9	0		
‎~	`	@	#	$	%	^	&	•	C	°	_	−
ZWJ	!	٬	٫	﷼	٪	÷	×	*	(	)	–	+
‎'	۱	۲	۳	۴	۵	۶	۷	۸	۹	۰	-	=
‎------------------------------------------------------------------------------------------------------------

‎			€			ٖ	ٰ	ٓ					\
‎	ْ	ٌ	ٍ	ً	ُ	ِ	َ	ّ	[	]	{	}	|
‎	ض	ص	ث	ق	ف	غ	ع	ه	خ	ح	ج	چ	/
-------------------------------------------------------------------------------------------------------------
‎											
‎			ىـ	ٕ	ٔ	ٱ		﴾	﴿	;	"
‎	ؤ	ئ	ي	إ	أ	آ	ء	«	»	:	؛
‎	ش	س	ی	ب	ل	ا	ت	ن	م	ک	گ
‎------------------------------------------------------------------------------------------------------------
‎										
‎		ۀ			ZWJ		'	,	…	?
‎	ك	ة	ژ	LRM	ZWNJ	RLM	ـ	<	>	؟
‎	ظ	ط	ز	ر	ذ	د	پ	و	.	،
‎------------------------------------------------------------------------------------------------------------
‎
‎					No-Break Space فاصله‌یِ نشکن
‎					Zero-Width Non-Joiner فاصله‌یِ مجازی
‎					Space فاصله
=============================================================================================================
ZWJ: Zero-Width Joiner اتصالِ مجازی
‎٬: ‎جداکننده‌یِ هزارها 	‎۲٬۳۴۱
‎٫: ‎جداکننده‌یِ اعشار 	‎۱٫۴
‎﴾﴿: ‎کمان‌هایِ تزئینی
LRM: Left-to-Right Mark نشانه‌یِ چپ‌به‌راست
RLM: Right-to-Left Mark نشانه‌یِ راست‌به‌چپ
ZWNJ: Zero-Width Non-Joiner فاصله‌یِ مجازی


=====================================Nowdabire (Optimal) 2.0 - Ordibeheŝt e ’96==============================
`	′	″	‴							Ø	≠	±
~	¹	²	³	£	€	÷	×	•	LRM	°	–	−
?	!	@	#	$	%	^	&	*	(	)	_	+
/	1	2	3	4	5	6	7	8	9	0	-	=
-------------------------------------------------------------------------------------------------------------
	“	”	·						≤	≥	{	}	
	‘	’	…	Ź					<	>	[	]	¦
	"	;	:										|
	'	,	.	Z	K	L	Y	T	H	F	J	Ĵ	\
-------------------------------------------------------------------------------------------------------------
								«	»		
	Ó	É	Ã	Á	Ú	Ś		‹	›	CAA	Ʌ
											
	O	E	Â	A	U	S	M	D	R	B	V
-------------------------------------------------------------------------------------------------------------
 										
			Ĝ	Í					Ɛ	
~										
`	W	Q	G	I	P	N	Ŝ	C	Ë	X
-------------------------------------------------------------------------------------------------------------

					No-Break Space

					Space
=============================================================================================================
LRM: Left-to-Right Mark
CAA: Combining Acute Accent, to insert acute on an arbitrary letter, for example: ʌ́.
