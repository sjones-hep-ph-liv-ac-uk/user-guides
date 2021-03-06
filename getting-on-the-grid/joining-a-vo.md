#Joining a Virtual Organisation

Your grid certificate identifies you to the grid as an individual user,
but it's not enough on its own to allow you to use grid resources;
you also need to join a Virtual Organisation (VO).
These are essentially just user groups - typically one per experiment -
and individual Resource Centres (RCs) can choose to support
work by users of a particular VO.
Most RCs support the four VOs associated with the
Large Hadron Collider (LHC) experiments.
The sign-up procedure varies from VO to VO.
UK-based VOs typically require a manual approval step,
while LHC VOs require an active CERN
account. If you are already part of an experiment that is
represented by a VO, they should provide you with any specific
instructions you need to join.

If you're interesting in using the grid but are not (yet) working as part of
a user community already represented by a VO, worry not.
GridPP have created a catch-all VO - [`gridpp`](https://voms.gridpp.ac.uk:8443/voms/gridpp/) - and four
Regional Virtual Organisations (RVOs) corresponding to the
four Tier 2s that can be joined to test out what the grid has to offer.
Once you have used these "incubator" VOs to see if the Grid meets
your needs, you can then think about creating your own
Virtual Organisation to represent your user community.

<table>
<tr>
<td align='center'><i class="fa fa-lightbulb-o" style='font-size:3em'></i></td>
<td>
Your user community may already have a VO associated
with it. Check the GridPP wiki page of
<a href='https://www.gridpp.ac.uk/wiki/GridPP_approved_VOs' target='_blank'>supported VOs</a>
to see if you can join that to speed things up.
</td>
</tr>
</table>

##Joining an incubator VO

<table>
<tr>
<td align='center'><i class="fa fa-lightbulb-o" style='font-size:3em'></i></td>
<td>
Some users have reported that the VOMS registration
described below fails
using the Safari web browser. We have tried and tested the process
using Mozilla Firefox.
</td>
</tr>
</table>

<table>
<tr>
<td align='center'><i class="fa fa-lightbulb-o" style='font-size:3em'></i></td>
<td>
Please ignore any "untrusted connection" warnings when
accessing the VOMS server pages. GridPP is aware that the
VOMS server uses unsigned certificates, but this situation is
unlikely to be resolved any time soon. 
</td>
</tr>
</table>

###Joining the GridPP VO

To join the
[`gridpp`](https://voms.gridpp.ac.uk:8443/voms/gridpp) VO, visit
[this page](https://voms.gridpp.ac.uk:8443/voms/gridpp/register/start.action)
using a browser that has your grid certificate installed
and follow the instructions.

###Joining a Regional VO
Likewise, you can join one of the four regional VOs by clicking
on the links in the table below 
and following the instructions.

| Regional VO | Resource Centres |
| --- | --- |
| <a href="https://voms.gridpp.ac.uk:8443/voms/vo.londongrid.ac.uk/register/start.action" target="_blank">`vo.londongrid.ac.uk`</a> | Brunel, UCL, Imperial College, Queen Mary, Royal Holloway |
| <a href="https://voms.gridpp.ac.uk:8443/voms/vo.northgrid.ac.uk/register/start.action" target="_blank">`vo.northgrid.ac.uk`</a> | Lancaster, Liverpool, Manchester, Sheffield, Daresbury Laboratory |
| <a href="https://voms.gridpp.ac.uk:8443/voms/vo.scotgrid.ac.uk" target="_blank">`vo.scotgrid.ac.uk`</a> | Glasgow, Edinburgh, Durham |
| <a href="https://voms.gridpp.ac.uk:8443/voms/vo.southgrid.ac.uk" target="_blank">`vo.southgrid.ac.uk`</a> | Birmingham, Bristol, Cambridge, Oxford, Warwick, Rutherford Appleton Laboratory, EFDA-JET, Sussex |

<table>
<tr>
<td align='center'><i class="fa fa-lightbulb-o" style='font-size:3em'></i></td>
<td>
Your VO membership request needs to be confirmed
manually by one of the VO administrators, so please wait
for the membership confirmation email to arrive before
proceeding. You may wish to keep an eye on your junk
folder(s) too.
</td>
</tr>
</table>

Once you have joined a VO, congratulations - you are ready to start
[using the grid](dirac-first-steps.html)!
