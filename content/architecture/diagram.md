# Cloud Foundry Architecture

<svg width="640" height="480" xmlns="http://www.w3.org/2000/svg">
 <!-- Created with SVG-edit - http://svg-edit.googlecode.com/ -->
 <defs>
  <marker refY="50" refX="50" markerHeight="5" markerWidth="5" viewBox="0 0 100 100" se_type="rightarrow" orient="auto" markerUnits="strokeWidth" id="se_marker_end_svg_55">
   <path stroke-width="10" stroke="#000000" fill="#000000" d="m100,50l-100,40l30,-40l-30,-40z"/>
  </marker>
  <marker refY="50" refX="50" markerHeight="5" markerWidth="5" viewBox="0 0 100 100" se_type="rightarrow" orient="auto" markerUnits="strokeWidth" id="se_marker_end_svg_56">
   <path stroke-width="10" stroke="#000000" fill="#000000" d="m100,50l-100,40l30,-40l-30,-40z"/>
  </marker>
  <marker refY="50" refX="50" markerHeight="5" markerWidth="5" viewBox="0 0 100 100" se_type="rightarrow" orient="auto" markerUnits="strokeWidth" id="se_marker_end_svg_57">
   <path stroke-width="10" stroke="#000000" fill="#000000" d="m100,50l-100,40l30,-40l-30,-40z"/>
  </marker>
  <marker refY="50" refX="50" markerHeight="5" markerWidth="5" viewBox="0 0 100 100" se_type="rightarrow" orient="auto" markerUnits="strokeWidth" id="se_marker_end_svg_58">
   <path stroke-width="10" stroke="#000000" fill="#000000" d="m100,50l-100,40l30,-40l-30,-40z"/>
  </marker>
 </defs>
 <g>
  <title>Layer 1</title>
  <g id="svg_40">
   <rect stroke="#000000" id="svg_20" height="301" width="569.99999" y="163" x="35" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#aaffff"/>
   <text xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="12" id="svg_24" y="454" x="492" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#3f3f3f">IaaS (AWS, Rackspace, Azure, Private)</text>
  </g>
  <g id="svg_41">
   <rect stroke="#000000" id="svg_1" height="240" width="553" y="179" x="44" stroke-width="2" fill="#56aaff"/>
   <text xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="15" id="svg_27" y="409" x="516" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#3f3f3f">Cloud Foundry PaaS</text>
  </g>
  <rect stroke="#000000" id="svg_14" height="97.99999" width="138" y="235" x="444" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#00bf5f"/>
  <rect stroke="#000000" id="svg_4" height="37" width="209" y="297" x="111" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#00bf5f"/>
  <rect stroke="#000000" id="svg_5" height="98" width="104.00001" y="236" x="329" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#00bf5f"/>
  <rect stroke="#000000" id="svg_6" height="99.99999" width="43" y="233" x="57" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#00bf5f"/>
  <rect stroke="#000000" id="svg_8" height="45" width="206" y="236" x="110" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#00bf5f"/>
  <rect id="svg_9" height="58" width="35" y="266" x="342" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#bfbf00"/>
  <rect stroke="#000000" id="svg_10" height="59" width="33" y="265" x="387" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#bfbf00"/>
  <rect id="svg_12" height="62" width="34" y="261" x="497" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#bfbf00"/>
  <rect id="svg_13" height="63" width="35" y="260" x="538" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#bfbf00"/>
  <rect stroke="#000000" id="svg_15" height="79" width="203" y="20" x="47" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#000000"/>
  <rect stroke="#000000" id="svg_16" height="63" width="177.99999" y="33" x="430" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#000000"/>
  <rect id="svg_17" height="37" width="37" y="49" x="60" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#000000"/>
  <rect id="svg_18" height="38" width="45" y="50" x="127" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#000000"/>
  <rect id="svg_19" height="40" width="39" y="46" x="199" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#000000"/>
  <g id="svg_33">
   <rect id="svg_3" height="32" width="537" y="345" x="53" stroke-width="2" stroke="#000000" fill="#00bf5f"/>
   <text xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="20" id="svg_32" y="367" x="322" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Messaging (NATS)</text>
  </g>
  <g id="svg_35">
   <rect stroke="#000000" id="svg_7" height="36" width="532" y="187" x="54" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" fill="#00bf5f"/>
   <text xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="20" id="svg_34" y="213" x="323" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Routers</text>
  </g>
  <text xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="20" id="svg_36" y="265" x="217" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Cloud Controllers</text>
  <rect id="svg_37" height="62" width="34" y="261" x="454" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#bfbf00"/>
  <text xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="20" id="svg_38" y="319" x="207" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Stagers</text>
  <text transform="rotate(-90 77 284.5)" xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="12" id="svg_39" y="289" x="77" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Health Manager</text>
  <text xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="18" id="svg_42" y="255" x="380" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Services</text>
  <text id="svg_43" xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="17" y="255" x="514" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Execution agents</text>
  <path id="svg_44" d="m451.06476,66.81604c-0.82422,-1.49108 -1.83749,-2.69695 -2.85049,-3.54033c-1.17841,0.86499 -2.61981,1.39123 -4.18524,1.39123c-1.57324,0 -3.00684,-0.52831 -4.19269,-1.39123c-1.01367,0.84338 -2.01892,2.04925 -2.85095,3.54033c-1.91925,3.45898 -2.12531,7.00756 -0.46936,7.92815c0.74152,0.41396 1.52374,0.10504 2.32324,-0.66937c-0.14032,0.78474 -0.22266,1.63637 -0.22266,2.52811c0,3.95738 1.54065,7.16306 3.43555,7.16306c1.13635,0 1.70508,-1.16772 1.97687,-2.95544c0.27216,1.78771 0.84052,2.95544 1.97723,2.95544c1.89484,0 3.43546,-3.20568 3.43546,-7.16306c0,-0.89174 -0.08261,-1.74336 -0.23047,-2.52811c0.80704,0.77441 1.58984,1.08333 2.33105,0.66937c1.65567,-0.92059 1.4418,-4.46918 -0.47754,-7.92815zm-7.03574,-3.49915c3.18848,0 5.77499,-2.58574 5.77499,-5.77496s-2.58652,-5.77594 -5.77499,-5.77594c-3.18817,0 -5.77472,2.58577 -5.77472,5.77594s2.58655,5.77496 5.77472,5.77496z" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#000000"/>
  <path id="svg_46" d="m494.06476,76.81604c-0.82422,-1.49108 -1.83746,-2.69695 -2.85049,-3.54033c-1.17841,0.86499 -2.61981,1.39123 -4.18524,1.39123c-1.57324,0 -3.00684,-0.52831 -4.19269,-1.39123c-1.01367,0.84338 -2.01892,2.04925 -2.85095,3.54033c-1.91925,3.45898 -2.12531,7.00756 -0.46936,7.92815c0.74152,0.41396 1.52374,0.10506 2.32324,-0.66936c-0.14032,0.78475 -0.22266,1.63637 -0.22266,2.52811c0,3.95738 1.54065,7.16306 3.43555,7.16306c1.13635,0 1.70508,-1.16772 1.97687,-2.95544c0.27216,1.78772 0.84052,2.95544 1.97723,2.95544c1.89484,0 3.43546,-3.20568 3.43546,-7.16306c0,-0.89174 -0.08258,-1.74335 -0.23047,-2.52811c0.80707,0.77442 1.58984,1.08333 2.33105,0.66936c1.6557,-0.92059 1.44183,-4.46917 -0.47754,-7.92815zm-7.03574,-3.49915c3.18848,0 5.77499,-2.58574 5.77499,-5.77496s-2.58652,-5.77594 -5.77499,-5.77594c-3.18817,0 -5.77472,2.58576 -5.77472,5.77594s2.58655,5.77496 5.77472,5.77496z" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#000000"/>
  <path id="svg_47" d="m535.06476,73.81604c-0.82422,-1.49108 -1.83746,-2.69695 -2.85052,-3.54033c-1.17841,0.86499 -2.61975,1.39123 -4.18518,1.39123c-1.57324,0 -3.00684,-0.52831 -4.19275,-1.39123c-1.01367,0.84338 -2.01886,2.04925 -2.85095,3.54033c-1.91919,3.45898 -2.12524,7.00756 -0.46936,7.92815c0.74158,0.41396 1.5238,0.10506 2.32324,-0.66936c-0.14026,0.78475 -0.22266,1.63637 -0.22266,2.52811c0,3.95738 1.54065,7.16306 3.43561,7.16306c1.13629,0 1.70502,-1.16772 1.97687,-2.95544c0.27209,1.78772 0.84045,2.95544 1.97717,2.95544c1.8949,0 3.43549,-3.20568 3.43549,-7.16306c0,-0.89174 -0.08258,-1.74335 -0.23047,-2.52811c0.80707,0.77442 1.58984,1.08333 2.33105,0.66936c1.6557,-0.92059 1.44183,-4.46917 -0.47754,-7.92815zm-7.03571,-3.49915c3.18848,0 5.77496,-2.58572 5.77496,-5.77495s-2.58649,-5.77594 -5.77496,-5.77594c-3.18817,0 -5.77478,2.58576 -5.77478,5.77594s2.58661,5.77495 5.77478,5.77495z" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#000000"/>
  <text xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="17" id="svg_48" y="53" x="508" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Users</text>
  <path id="svg_49" d="m568.06476,61.81604c-0.82422,-1.49108 -1.83746,-2.69695 -2.85052,-3.54033c-1.17841,0.86499 -2.61975,1.39123 -4.18518,1.39123c-1.57324,0 -3.00684,-0.52831 -4.19275,-1.39123c-1.01367,0.84338 -2.01886,2.04925 -2.85095,3.54033c-1.91919,3.45898 -2.12524,7.00756 -0.46936,7.92815c0.74158,0.41396 1.5238,0.10506 2.32324,-0.66936c-0.14026,0.78475 -0.22266,1.63637 -0.22266,2.52811c0,3.95738 1.54065,7.16306 3.43561,7.16306c1.13629,0 1.70502,-1.16772 1.97687,-2.95544c0.27209,1.78772 0.84045,2.95544 1.97717,2.95544c1.8949,0 3.43549,-3.20568 3.43549,-7.16306c0,-0.89174 -0.08258,-1.74335 -0.23047,-2.52811c0.80707,0.77442 1.58984,1.08333 2.33105,0.66936c1.6557,-0.92059 1.44183,-4.46917 -0.47754,-7.92815zm-7.03571,-3.49915c3.18848,0 5.77496,-2.58572 5.77496,-5.77495s-2.58649,-5.77594 -5.77496,-5.77594c-3.18817,0 -5.77478,2.58576 -5.77478,5.77594s2.58661,5.77495 5.77478,5.77495z" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#000000"/>
  <path id="svg_50" d="m597.06476,72.81604c-0.82422,-1.49108 -1.83746,-2.69695 -2.85052,-3.54033c-1.17841,0.86499 -2.61975,1.39123 -4.18518,1.39123c-1.57324,0 -3.00684,-0.52831 -4.19275,-1.39123c-1.01367,0.84338 -2.01886,2.04925 -2.85095,3.54033c-1.91919,3.45898 -2.12524,7.00756 -0.46936,7.92815c0.74158,0.41396 1.5238,0.10506 2.32324,-0.66936c-0.14026,0.78475 -0.22266,1.63637 -0.22266,2.52811c0,3.95738 1.54065,7.16306 3.43561,7.16306c1.13629,0 1.70502,-1.16772 1.97687,-2.95544c0.27209,1.78772 0.84045,2.95544 1.97717,2.95544c1.8949,0 3.43549,-3.20568 3.43549,-7.16306c0,-0.89174 -0.08258,-1.74335 -0.23047,-2.52811c0.80707,0.77442 1.58984,1.08333 2.33105,0.66936c1.6557,-0.92059 1.44183,-4.46917 -0.47754,-7.92815zm-7.03571,-3.49915c3.18848,0 5.77496,-2.58574 5.77496,-5.77496s-2.58649,-5.77594 -5.77496,-5.77594c-3.18817,0 -5.77478,2.58576 -5.77478,5.77594s2.58661,5.77496 5.77478,5.77496z" fill-opacity="0" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="#000000"/>
  <text id="svg_51" xml:space="preserve" text-anchor="middle" font-family="Sans-serif" font-size="17" y="39" x="149" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="0" stroke="#000000" fill="#000000">Developers</text>
  <line marker-end="url(#se_marker_end_svg_55)" id="svg_55" y2="200" x2="153" y1="97" x1="108" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="none"/>
  <line marker-end="url(#se_marker_end_svg_56)" id="svg_56" y2="243" x2="154" y1="206" x1="154" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="none"/>
  <line marker-end="url(#se_marker_end_svg_57)" id="svg_57" y2="201" x2="471" y1="95" x1="519" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="none"/>
  <line marker-end="url(#se_marker_end_svg_58)" id="svg_58" y2="264" x2="470" y1="205" x1="470" stroke-linecap="null" stroke-linejoin="null" stroke-dasharray="null" stroke-width="2" stroke="#000000" fill="none"/>
 </g>
</svg>

### Sources
1. [Cloudfoundry Architecture by ramnivas2)](http://www.slideshare.net/ramnivas2/cloudfoundry-architecture)