java c
SCHOOL OF ENGINEERING 
Year 2 Laboratories 


VI- Vibration 
MECH215: Dynamic Systems 
Notation Symbol Meaning Units m Suspended mass kg x(t) Deflection of the mass m y(t) End deflection of the spring m k Spring stiffness N/m c Damping coefficient Ns/m w Frequency rad/s wd Frequency of free-damped oscillation rad/s wn Natural frequency rad/s ξ Damping ratio - 
1 Introduction The dynamical response of systems to various disturbances forms a major field of study in   engineering. For example, the behaviour of suspension units,   loudspeaker cones and more   generally, structures, hydraulic systems and many others can be predicted using a system   modelling   approach.   This   approach   will   be   used   in   the   experiment   to   study   the   behaviour   of   a   second-order   mechanical   system,   and   essentially   the   general   procedure   for   all   such   problems   is   to:
•             Build a   mathematical   model of the system
•             Predict the   behaviour of the system   using this   model
•          Compare   the   predicted   with   the   real   behaviour   and   draw   any   relevant   conclusions
This   exercise   is   related to the   MECH215/ENGG301   notes on Free Vibrations and Forced Harmonic Vibrations.
1.1 Aims and Objectives 
The aims   of   this lab is to illustrate the concepts or   free and   forced   vibrations   through a real   dynamic system   and the objectives of this virtual   lab   are:
•          To    understand   the   difference    between   free    response    and   harmonic   forced   response   for   an oscillating   system.
•          To   understand the   effects   of   different   levels   of   damping   on   an   oscillating.
•          To   understand   how   to   use   experimental   results   to   identify   the   parameters   of   a   dynamical   system.
2 Background 
2.1 The System Model 


Figure 1 Model of the oscillator 
The system consists of a   mass-spring   damper arrangement   as   shown   is   Fig.   1:
•            mis the suspended   mass   (kg)
•             k   is the spring   stiffness   (N/m)
•            c   is the damping coefficient   (Ns/m)
•            y(t)   is the end deflection   of the   spring   (m)
•            x(t)   is the   deflection of the   mass   (m)
To   obtain the   equation   of   motion   of the   system, the forces   that   are   associated   with   the   mass   are   sum together. Then applying the   Newton’s Second   Law of motion yieldseq.   1.
(eq.1) Equation   1   can   then   be   compared   to   eq.2   below,   which   is   the   standard   form   of   a   second   order   dynamical   system   and   which   can   be   found   in   the   lectures'   slides.   By   comparing   the   coefficients   from   eq.1   and   eq.2,   the   values   for   the   damping   ratio   ξ,   natural   frequency   ωn    and   the   input   u(t)   (which   is equal toy(t)   is this   particular case) can   be determined.(eq.2) 
2.2 Predicted Responses The    response    x(t)    of    the      system      will      depend      on      the      input      y(t)      and      the      initial      conditions.      In   addition,    x(t)    will    depend    on    ξ    and    ωn.      However      in    the      experiment    only      ξ      will    vary.      We      will   examine   two   types   of   response:   the   free   response   (when   y(t)=0,   i.e.   no   input)   and   the   sinusoidal   forced   response   (when y(t)   is a sinusoid).
2.2.1 Predicted Free Response 
The   initial   conditions   and   the   input   of   the   second   order   free   response   system   are   given as   (there   is only an   initial displacement, the   initial   speed   is   zero):

Applying   these   conditions   to   eq.2, giveseq.3   in   the   classical   form.
(eq.3) 
If ξ < 1 (underdamped case), then the standard solution can be written in the form. of eq. 4.
(eq.4) 
Where the damped frequency  can   be calculated as
(eq.5) 
where A(t)   is the amplitude and  is the   phase shift,   defined   as

Note:             If   ξ   >   0,   then   the   frequency   of   the   free   response   is not the   natural   frequency   ωn       but   the   damped frequency ωd.    A sketch of x(t), which   is   modelled   by   eq.4,   can   be   seen   in fig.2.

Figure 2: Time domain plot of response indicating the damped frequency and the amplitude decay 
The   decay   of the   oscillatory   response   is   often   characterised   by   its logarithmic decrement defined   in   eq.   6:
(eq.6)
where   Ai      is   the   amplitude   of   the   ith    peak   at   any   time   axis   and   Ai+1      is   the   amplitude   for   the   (i+1)th   peak.   Notice that the   logarithm decrement   is   independent of the   initial condition x0.
2.2.2 Predicted Sinusoidal Response 
The   initial conditions and   input of the second-order forced   response   system   are   now   given   as:

Here   ω0   is   the   input   frequency   and   Y   is   the   input   amplitude   of   the   imposed   displacement.   In   this   case the steady-state   response can   be written as   shown   by   eq.7.
(eq.7) 
The    forced    (steady-state)    response    is    another    sinusoid      of    the    same    frequency      as    y(t),      but    of amplitude Yβ(ω0) and a phase shift of   ϕH   (ω0)   rad/s.   A   sketch   of the   response   can   be   seen   in   fig.3.

Figure 3: Phase and amplitude for a forced vibration system 
From eq.7, the amplification factor   β and the   phase   shift   ϕH      can   be   calculated   using   eq.   8   and   eq.9.
(eq.8) 
(eq.9)
The   phase shift   is simply the   lag of the   response   behind the   input,   multiplied   by the   input frequency. Sketching the values of   the amplification factor   and the   phase   against   ω0   for   different   values of ξ yields a family   of   curves,   fig.4.

Figure 4: Amplification factor and phase shift example plots for a forced vibration system 
The   negative angle   indicates   phase   lag.
The   maximum amplitude   is   reached for ω0    =   ωr    , where  is the   resonance frequency. The   maximum amplitude   is then given   by the formula
(eq.10)
Concerning the   phase   plots, we   have the   property
(eq.11) 
independently of the value of the damping   ratio.
For   systems where   a   peak   in the   amplitude   curve   exists, the ‘strength’   of the   peak   is   measured   by   the bandwidth, defined as the frequency   range over which,   eq.12:
(eq.12) 
A sketch to   illustrate the   bandwidth   is shown   by fig.5:

Figure 5: Definition of bandwidth 
It can   be shown that   for small v代 写MECH215: Dynamic SystemsMatlab
代做程序编程语言alues   of   ξ,
(eq.12) 
3 Health and Safety 
There are   no significant   hazards   in this experiment.
Students   are   reminded that they   are   required   by   law to   comply with the   Department’s   basic   rules   of   lab safety given to them at the   start   of the   semester.
4 Experimental Procedure The   necessary   data   for   the   experiments   are:   mass   of   each   disc   =   1kg;   mass   of   frame   +   damper   piston   =   2.1kg.   Thus   the   total   mass   is   4.1   kg.   All   tables   require   a   title   and   all   recordings   require   unitsThis   is   a virtual   lab. The   response   of the   oscillator   is then   simulated   and   animated   using   a   Matlab   program.   Friction   forces   and   measurements   errors   are   taken   into   account   in   this   program.   They   are generated   randomly   based   on the   student   number. As   a   consequence,   each student   will   work   with   unique experimental   measurements.
4.1 D1: Free Response 
Use the   Matlab   program “   Lab_VI_virtual_simulation.m” to simulate the oscillator.
i. Undamped case:   In the   Matlab   program,   choose the   option ‘no   damping’   case,   choose   an   initial   position   of the   mass   and   a   simulation   duration.   Repeat the   procedure   5 times with   the   same   configuration   (but   changing   the   run   number).   From   the   recorded   results,   find   the   period   Tn      and   determine   the   natural   frequency   ωn.   Assume   here   that   ξ   is   negligible.   Determine also the stiffness   of the   spring.
ii. Damped case:   Now choose the   low   of   damping,   repeat   5   runs   and for   each   run,   report   the   amplitude value for the two first   peaks.
4.2 D2: Sinusoidal Response 
The    amplification    factor    β(ω0)      is      equal      to      the      ratio      of      the      response      amplitude      to      the      input   amplitude.
i.          With   the    damper    at    its    low      level    of    damping,    determine    the      amplification    factor    and   phase   for   increasing   frequency   and   use   this   data   to   construct   amplification   and   phase   curves.   Use frequency values of 0.4 – 4   Hz   and take   at   least   10   recordings.
ii.       Now    for    the   critically    damped    case,    i.e.    so   that   there    is just no    overshoot    in    the   free   response,   repeat the   procedure   for   measuring   amplification   and   phase   and   plot the   new   curves on your original   graph.
iii.    Now for the   intermediate value of damping   between,   repeat   the   procedure   for   measuring   amplification and   phase, and again   plot the   new curves   on   your   original   graph.
5 Tables 
Table 1: Free response for natural frequency Run Number T1 (s) T2 (s) Tn (s) ωn (rad/s) k (N/m) 





Average ωn and k 


Table 2: Free response for lowest damping ratio Run Number A0 (mm) A1 (mm) A0/A1 



Average A0/A1 

*Zero calibration   must   be done   in this step
Table 3: Sinusoidal response of the lowest damping ratio Run Number Input Frequency ω0 (Hz) Input Frequency ω0 (rad/s) Amplification, β(ω0) Phase (rad), ϕH(ω0) 






Table 4: Sinusoidal response of critical damping ratio ξ=1 Run Number Input Frequency ω0 (Hz) Input Frequency ω0 (rad/s) Amplification, β(ω0) Phase (rad), ϕH(ω0) 






Table 5: Sinusoidal response of intermediate damping ratio Run Number Input Frequency ω0 (Hz) Input Frequency ω0 (rad/s) Amplification, β(ω0) Phase (rad), ϕH(ω0) 





6 Technical Note Submission 
6.1 Assessment Criteria 
• Technical Writing 5% 
Correct spelling, grammar, formatting and concise.
• Introduction 10% 
Roughly 500 words. This should   include a   brief   context/why this   lab   is   important, what   you did,   how you did   it and   a   brief   summary   of the   results.
• Results, calculations and graphs 60 % 
PartI: Free Response 
1.          Show the two tables of   results for the free   response   (   i.e.   table   1   and   2)
2.          Calculate the average   natural frequency   (ωn), the average   stiffness   (k)   and for   the   low damping case, the   average amplitude   ratio   (A0/A1).
3.          Calculate the   low   damping   ratio   ()   using the   logarithmic decrement formula.
Part II: Forced Response 
1.          Show the three tables of   results for the forced   response   (i.e.   table   3,   4   and   5)
2.          Plot graphs for amplification factor vs   input   frequency   (amplification   factor   plot)   and   phase shift vs   input frequency   (phase   plot) considering the three   levels   of
damping.   (Refer figure 4)
3.          Estimate the   natural frequency   using the   phase   plot for the low value of   damping.   (This   is where the   phase =   -π/2   rad/s)
4.          Compare the   natural frequency obtained from   II-3 and   I-2.
5.          Estimate the damping   ratio via the   amplification factor   plot   for the low value   of   damping   using:a.          The value of the   maximum amplitude.b.         The value of the   resonance frequency.c.          The   bandwidth approximation.
6.          Calculate the average of the damping   ratio for   the low value   of   damping   i.e.   5a,   5b, 5cand   I-3.
7.          Estimate the damping   ratio via the   amplification   plot for the intermediate value   of damping   using:a.          The value of the   maximum amplitude.b.         The value of the   resonance frequency.c.          The   bandwidth approximation.
8.          Calculate the   average of the damping   ratio for the intermediate value   of   damping   i.e. 7a,   7band   7c.
• Discussion 20% 
Draw   meaning from each   plot.   Match   results to theory.   Did what   happen   match what   should   have   happened?
Comment   upon the shapes of your amplitude and   phase   curves.
Give an example of a   real   mechanical system that   can   be   represented   by   a   similar   oscillating system, as   has   been seen   in the   lab   exercise.
• Conclusion 5% 
Draw   numerical conclusions from each   plot. Summarise findings   of   numerical experiments
6.2 Submission Instructions 
Download the Technical Note Template for the   Lab VI available on Canvas.
Rename   the   document   to   include   your    name    before   submitting    it   –   for   example   “VI   Technical   Note John Smith.docx”   .
Complete   the   technical   note   and   upload   it   on   Canvas   with   the    link   available   in   the   Virtual    Lab   section.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
