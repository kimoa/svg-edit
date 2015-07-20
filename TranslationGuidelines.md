To commit translations to the main code base, please see: [CommitPolicy](CommitPolicy.md)

Under construction

<a href='Hidden comment: 
[http://imgh.us/SVG-edit_Languages.svg http://imgh.us/SVG-edit_Languages.jpg]

shows the status of translations for each SVG-edit language file.<br/>
'></a>

---


[Introduction](TranslationGuidelines#Introduction.md) Explanation of this document.<br />
[IDs Details](TranslationGuidelines#IDs_Details.md) Describes the IDs.<br />
[js\_strings](TranslationGuidelines#JavaScript_strings_(js_strings).md) Describes the JavaScript strings.


# Introduction #

This page lists the existing IDs in the language files, and explains what they "technically" represent, for a meaningful - yet simple - translation of the SVG-edit interface.

<font color='Blue'>New ID since the last version</font><br />
<font color='Green'>Active ID</font><br />
<font color='Orange'>ID made obsolete last version</font><br />
<font color='Red'>Obsolete ID</font><br />

There is also a block of JavaScript strings, at the end of each language file. Their second part needs to be translated.

The current available languages files can be found [here](http://code.google.com/p/svg-edit/source/browse/#svn/trunk/editor/locale). Click on the language file you want, then select "View Raw file" to display the file and save it as a .js file that you can edit.

This page is sorted in the same order as the language files themselves.

Notes:
  * a '%string' is a value and must not be translated. Ex: '%s'.
  * \n inside a long line:<br>
</li></ul><blockquote>Long lines are sometimes split with a<br>
\nwhich must not be translated. It may be moved<br>
\ninto the sentences<br>
\nfor verbose languages.<br>
</blockquote><ul><li>References to shortcuts (numbers or words inside a pair of "[ ]" brackets still appearing in a language file must be deleted from the line.</li></ul>

<hr />

<h1>IDs Details</h1>

<font color='Green'>
<h2>align_relative_to</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To align objects relatively to either objects or the page.</th></thead><tbody>
<tr><td>Default language</td><td>Align relative to ...                                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                                    </td></tr>
<tr><td>Obsolete since</td><td>-                                                                      </td></tr></tbody></table>

<font color='Red'>
<h2>angleLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The angle of rotation applied to an object.</th></thead><tbody>
<tr><td>Default language</td><td>angle:                                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                     </td></tr>
<tr><td>Obsolete since</td><td>2.5                                                     </td></tr></tbody></table>

<font color='Green'>
<h2>bkgnd_color</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the background color / the opacity.</th></thead><tbody>
<tr><td>Default language</td><td>Change background color/opacity                           </td></tr>
<tr><td>In use since</td><td>2.4                                                       </td></tr>
<tr><td>Obsolete since</td><td>-                                                         </td></tr></tbody></table>

<font color='Green'>
<h2>circle_cx</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the horizontal coordinate cx of a circle.</th></thead><tbody>
<tr><td>Default language</td><td>Change circle's cx coordinate                                   </td></tr>
<tr><td>In use since</td><td>2.4                                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                                               </td></tr></tbody></table>

<font color='Green'>
<h2>circle_cy</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the vertical coordinate cy of a circle.</th></thead><tbody>
<tr><td>Default language</td><td>Change circle's cy coordinate                                 </td></tr>
<tr><td>In use since</td><td>2.4                                                           </td></tr>
<tr><td>Obsolete since</td><td>-                                                             </td></tr></tbody></table>

<font color='Green'>
<h2>circle_r</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the radius of a circle.</th></thead><tbody>
<tr><td>Default language</td><td>Change circle's radius                        </td></tr>
<tr><td>In use since</td><td>2.4                                           </td></tr>
<tr><td>Obsolete since</td><td>-                                             </td></tr></tbody></table>

<font color='Blue'>
<h2>connector_no_arrow</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Option indicating that the line should not have arrows.</th></thead><tbody>
<tr><td>Default language</td><td>No arrow                                                            </td></tr>
<tr><td>In use since</td><td>2.5                                                                 </td></tr>
<tr><td>Obsolete since</td><td>-                                                                   </td></tr></tbody></table>

<font color='Blue'>
<h2>copyrightLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence start</i>. Prefix to "SVG-edit" credit in bottom-right corner.</th></thead><tbody>
<tr><td>Default language</td><td>Powered by                                                                </td></tr>
<tr><td>In use since</td><td>2.5                                                                       </td></tr>
<tr><td>Obsolete since</td><td>-                                                                         </td></tr></tbody></table>

<font color='Purple'>
<h2>cornerRadiusLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. Value of the radius of the corners, for a rectangle with rounded corners. Note: This text used to be "Corner Radius:" and was a label. As of 2.5 it refers to the tooltip text</th></thead><tbody>
<tr><td>Default language</td><td>Change Rectangle Corner Radius                                                                                                                                                             </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                                                                                        </td></tr>
<tr><td>Obsolete since</td><td>                                                                                                                                                                                           </td></tr></tbody></table>

<font color='Green'>
<h2>curve_segments</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Type of segment: curved segment, as opposed to straight line.</th></thead><tbody>
<tr><td>Default language</td><td>Curve                                                                     </td></tr>
<tr><td>In use since</td><td>2.4                                                                       </td></tr>
<tr><td>Obsolete since</td><td>-                                                                         </td></tr></tbody></table>

<font color='Green'>
<h2>ellipse_cx</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the horizontal coordinate cx of an ellipse.</th></thead><tbody>
<tr><td>Default language</td><td>Change ellipse's cx coordinate                                    </td></tr>
<tr><td>In use since</td><td>2.4                                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                                 </td></tr></tbody></table>

<font color='Green'>
<h2>ellipse_cy</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the vertical coordinate cy of an ellipse.</th></thead><tbody>
<tr><td>Default language</td><td>Change ellipse's cy coordinate                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                                               </td></tr></tbody></table>

<font color='Green'>
<h2>ellipse_rx</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the horizontal radius x of an ellipse.</th></thead><tbody>
<tr><td>Default language</td><td>Change ellipse's x radius                                    </td></tr>
<tr><td>In use since</td><td>2.4                                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                                            </td></tr></tbody></table>

<font color='Green'>
<h2>ellipse_ry</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the vertical radius y of an ellipse.</th></thead><tbody>
<tr><td>Default language</td><td>Change ellipse's y radius                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                        </td></tr>
<tr><td>Obsolete since</td><td>-                                                          </td></tr></tbody></table>

<font color='Green'>
<h2>fill_color</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the fill color of an object.</th></thead><tbody>
<tr><td>Default language</td><td>Change fill color                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                  </td></tr></tbody></table>

<font color='Red'>
<h2>fill_tool_bottom</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The inner painting of an object.</th></thead><tbody>
<tr><td>Default language</td><td>fill:                                        </td></tr>
<tr><td>In use since</td><td>2.4                                          </td></tr>
<tr><td>Obsolete since</td><td>2.5                                          </td></tr></tbody></table>

<font color='Green'>
<h2>fitToContent</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective or past participle</i>. Adjusted to the content of the drawing, cropped.</th></thead><tbody>
<tr><td>Default language</td><td>Fit to Content                                                                       </td></tr>
<tr><td>In use since</td><td>2.4                                                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                    </td></tr></tbody></table>

<font color='Green'>
<h2>fit_to_all</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To adjust the zoom level to include everything drawn in all layers.</th></thead><tbody>
<tr><td>Default language</td><td>Fit to all content                                                              </td></tr>
<tr><td>In use since</td><td>2.4                                                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                                                               </td></tr></tbody></table>

<font color='Green'>
<h2>fit_to_canvas</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To adjust the zoom level to the canvas dimensions.</th></thead><tbody>
<tr><td>Default language</td><td>Fit to canvas                                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                            </td></tr>
<tr><td>Obsolete since</td><td>-                                                              </td></tr></tbody></table>

<font color='Green'>
<h2>fit_to_layer_content</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To adjust the zoom level to include everything in the current layer.</th></thead><tbody>
<tr><td>Default language</td><td>Fit to layer content                                                             </td></tr>
<tr><td>In use since</td><td>2.4                                                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                </td></tr></tbody></table>

<font color='Green'>
<h2>fit_to_sel</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To adjust the zoom level to include all the selected objects.</th></thead><tbody>
<tr><td>Default language</td><td>Fit to selection                                                          </td></tr>
<tr><td>In use since</td><td>2.4                                                                       </td></tr>
<tr><td>Obsolete since</td><td>-                                                                         </td></tr></tbody></table>

<font color='Green'>
<h2>font_family</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the font-family of a text element.</th></thead><tbody>
<tr><td>Default language</td><td>Change Font Family                                       </td></tr>
<tr><td>In use since</td><td>2.4                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                        </td></tr></tbody></table>

<font color='Blue'>
<h2>idLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the ID of an element.</th></thead><tbody>
<tr><td>Default language</td><td>Identify the element                        </td></tr>
<tr><td>In use since</td><td>2.5                                         </td></tr>
<tr><td>Obsolete since</td><td>-                                           </td></tr></tbody></table>

<font color='Green'>
<h2>icon_large</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective</i>. Large, for the size of the icons.</th></thead><tbody>
<tr><td>Default language</td><td>Large                                              </td></tr>
<tr><td>In use since</td><td>2.4                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                  </td></tr></tbody></table>

<font color='Green'>
<h2>icon_medium</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective</i>. Average, for the size of the icons.</th></thead><tbody>
<tr><td>Default language</td><td>Medium                                               </td></tr>
<tr><td>In use since</td><td>2.4                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                    </td></tr></tbody></table>

<font color='Green'>
<h2>icon_small</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective</i>. Small, for the size of the icons.</th></thead><tbody>
<tr><td>Default language</td><td>Small                                              </td></tr>
<tr><td>In use since</td><td>2.4                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                  </td></tr></tbody></table>

<font color='Green'>
<h2>icon_xlarge</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective</i>. Extra large, for the size of the icons.</th></thead><tbody>
<tr><td>Default language</td><td>Extra Large                                              </td></tr>
<tr><td>In use since</td><td>2.4                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                        </td></tr></tbody></table>

<font color='Red'>
<h2>iheightLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Height.</th></thead><tbody>
<tr><td>Default language</td><td>height:             </td></tr>
<tr><td>In use since</td><td>2.4                 </td></tr>
<tr><td>Obsolete since</td><td>2.5                 </td></tr></tbody></table>

<font color='Green'>
<h2>image_height</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the height of an image.</th></thead><tbody>
<tr><td>Default language</td><td>Change image height                           </td></tr>
<tr><td>In use since</td><td>2.4                                           </td></tr>
<tr><td>Obsolete since</td><td>-                                             </td></tr></tbody></table>

<font color='Green'>
<h2>image_opt_embed</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To embed (include, integrate) the images as data (for local files)</th></thead><tbody>
<tr><td>Default language</td><td>Embed data (local files)                                                       </td></tr>
<tr><td>In use since</td><td>2.4                                                                            </td></tr>
<tr><td>Obsolete since</td><td>-                                                                              </td></tr></tbody></table>

<font color='Green'>
<h2>image_opt_ref</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To use the reference of the images (URLs of the images, instead of embedding them</th></thead><tbody>
<tr><td>Default language</td><td>Use file reference                                                                            </td></tr>
<tr><td>In use since</td><td>2.4                                                                                           </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                             </td></tr></tbody></table>

<font color='Green'>
<h2>image_url</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the URL of an image.</th></thead><tbody>
<tr><td>Default language</td><td>Change URL                                 </td></tr>
<tr><td>In use since</td><td>2.4                                        </td></tr>
<tr><td>Obsolete since</td><td>-                                          </td></tr></tbody></table>

<font color='Green'>
<h2>image_width</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the width of an image.</th></thead><tbody>
<tr><td>Default language</td><td>Change image width                           </td></tr>
<tr><td>In use since</td><td>2.4                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                            </td></tr></tbody></table>

<font color='Green'>
<h2>includedImages</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective or past participle</i>. Included, integrated, embedded images.</th></thead><tbody>
<tr><td>Default language</td><td>Included Images                                                            </td></tr>
<tr><td>In use since</td><td>2.4                                                                        </td></tr>
<tr><td>Obsolete since</td><td>-                                                                          </td></tr></tbody></table>

<font color='Red'>
<h2>iwidthLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Width.</th></thead><tbody>
<tr><td>Default language</td><td>width:             </td></tr>
<tr><td>In use since</td><td>2.4                </td></tr>
<tr><td>Obsolete since</td><td>2.5                </td></tr></tbody></table>

<font color='Green'>
<h2>largest_object</h2>
</font>
<table><thead><th>Description</th><th><i>Superlative adjective</i>. The largest object.</th></thead><tbody>
<tr><td>Default language</td><td>largest object                                   </td></tr>
<tr><td>In use since</td><td>2.4                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                </td></tr></tbody></table>

<font color='green'>
<h2>layer_delete</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To delete the current layer.</th></thead><tbody>
<tr><td>Default language</td><td>Delete Layer                             </td></tr>
<tr><td>In use since</td><td>2.4                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                        </td></tr></tbody></table>

<font color='green'>
<h2>layer_down</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To move the current layer down in the layer table.</th></thead><tbody>
<tr><td>Default language</td><td>Move Layer Down                                                </td></tr>
<tr><td>In use since</td><td>2.4                                                            </td></tr>
<tr><td>Obsolete since</td><td>-                                                              </td></tr></tbody></table>

<font color='green'>
<h2>layer_new</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. A new layer.</th></thead><tbody>
<tr><td>Default language</td><td>New Layer                </td></tr>
<tr><td>In use since</td><td>2.4                      </td></tr>
<tr><td>Obsolete since</td><td>-                        </td></tr></tbody></table>

<font color='green'>
<h2>layer_rename</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To give a new name to the current layer.</th></thead><tbody>
<tr><td>Default language</td><td>Rename Layer                                         </td></tr>
<tr><td>In use since</td><td>2.4                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                    </td></tr></tbody></table>

<font color='green'>
<h2>layer_up</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To move the current layer up in the layer table.</th></thead><tbody>
<tr><td>Default language</td><td>Move Layer Up                                                </td></tr>
<tr><td>In use since</td><td>2.4                                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                                            </td></tr></tbody></table>

<font color='green'>
<h2>layersLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The layers.</th></thead><tbody>
<tr><td>Default language</td><td>Layers:                 </td></tr>
<tr><td>In use since</td><td>2.4                     </td></tr>
<tr><td>Obsolete since</td><td>-                       </td></tr></tbody></table>

<font color='green'>
<h2>line_x1</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the horizontal coordinate x of the starting point, for a line.</th></thead><tbody>
<tr><td>Default language</td><td>Change line's starting x coordinate                                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                    </td></tr></tbody></table>

<font color='green'>
<h2>line_x2</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the horizontal coordinate x of the ending point, for a line.</th></thead><tbody>
<tr><td>Default language</td><td>Change line's ending x coordinate                                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                  </td></tr></tbody></table>

<font color='green'>
<h2>line_y1</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the vertical coordinate y of the starting point, for a line.</th></thead><tbody>
<tr><td>Default language</td><td>Change line's starting y coordinate                                                </td></tr>
<tr><td>In use since</td><td>2.4                                                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                  </td></tr></tbody></table>

<font color='green'>
<h2>line_y2</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the vertical coordinate y of the ending point, for a line.</th></thead><tbody>
<tr><td>Default language</td><td>Change line's ending y coordinate                                                </td></tr>
<tr><td>In use since</td><td>2.4                                                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                </td></tr></tbody></table>

<font color='blue'>
<h2>linecap_butt</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. To made the end of a line stop exactly at its end coordinate.</th></thead><tbody>
<tr><td>Default language</td><td>Linecap: Butt                                                             </td></tr>
<tr><td>In use since</td><td>2.5                                                                       </td></tr>
<tr><td>Obsolete since</td><td>-                                                                         </td></tr></tbody></table>

<font color='blue'>
<h2>linecap_round</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. To made the end of a line end rounded.</th></thead><tbody>
<tr><td>Default language</td><td>Linecap: Round                                     </td></tr>
<tr><td>In use since</td><td>2.5                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                  </td></tr></tbody></table>

<font color='blue'>
<h2>linecap_round</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. To made the end of a line end square.</th></thead><tbody>
<tr><td>Default language</td><td>Linecap: Square                                   </td></tr>
<tr><td>In use since</td><td>2.5                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                 </td></tr></tbody></table>

<font color='blue'>
<h2>linejoin_bevel</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. To make line joints use straight, cut off edges.</th></thead><tbody>
<tr><td>Default language</td><td>Linejoin: Bevel                                              </td></tr>
<tr><td>In use since</td><td>2.5                                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                                            </td></tr></tbody></table>

<font color='blue'>
<h2>linejoin_miter</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. To make line joints use regular, usually pointy edges.</th></thead><tbody>
<tr><td>Default language</td><td>Linejoin: Miter                                                    </td></tr>
<tr><td>In use since</td><td>2.5                                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                                  </td></tr></tbody></table>

<font color='blue'>
<h2>linejoin_round</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. To make line joints use round edges.</th></thead><tbody>
<tr><td>Default language</td><td>Linejoin: Round                                  </td></tr>
<tr><td>In use since</td><td>2.5                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                </td></tr></tbody></table>

<font color='blue'>
<h2>main_icon</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The main (application) menu.</th></thead><tbody>
<tr><td>Default language</td><td>Main Menu                                </td></tr>
<tr><td>In use since</td><td>2.5                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                        </td></tr></tbody></table>

<font color='blue'>
<h2>mode_connect</h2>
</font>
<table><thead><th>Description</th><th>Verb. Option to connect two objects with a line.</th></thead><tbody>
<tr><td>Default language</td><td>Connect two objects                             </td></tr>
<tr><td>In use since</td><td>2.5                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                               </td></tr></tbody></table>

<font color='green'>
<h2>page</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The page.</th></thead><tbody>
<tr><td>Default language</td><td>page                  </td></tr>
<tr><td>In use since</td><td>2.4                   </td></tr>
<tr><td>Obsolete since</td><td>-                     </td></tr></tbody></table>

<font color='green'>
<h2>palette</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The palette, the painter's tool which holds all the available colors.</th></thead><tbody>
<tr><td>Default language</td><td>Click to change fill color, shift-click to change stroke color                    </td></tr>
<tr><td>In use since</td><td>2.4                                                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                 </td></tr></tbody></table>

<font color='green'>
<h2>path_node_x</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the horizontal coordinate x, for a node (point).</th></thead><tbody>
<tr><td>Default language</td><td>Change node's x coordinate                                             </td></tr>
<tr><td>In use since</td><td>2.4                                                                    </td></tr>
<tr><td>Obsolete since</td><td>-                                                                      </td></tr></tbody></table>

<font color='green'>
<h2>path_node_y</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the vertical coordinate y, for a node (point).</th></thead><tbody>
<tr><td>Default language</td><td>Change node's y coordinate                                           </td></tr>
<tr><td>In use since</td><td>2.4                                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                                    </td></tr></tbody></table>

<font color='green'>
<h2>rect_height</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the height of a rectangle.</th></thead><tbody>
<tr><td>Default language</td><td>Change rectangle height                          </td></tr>
<tr><td>In use since</td><td>2.4                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                </td></tr></tbody></table>

<font color='green'>
<h2>rect_rx</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the value of the radius of the corners, for a rectangle with rounded corners.</th></thead><tbody>
<tr><td>Default language</td><td>Change Rectangle Corner Radius                                                                      </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                 </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                   </td></tr></tbody></table>

<font color='green'>
<h2>rect_width</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the width of a rectangle.</th></thead><tbody>
<tr><td>Default language</td><td>Change rectangle width                          </td></tr>
<tr><td>In use since</td><td>2.4                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                               </td></tr></tbody></table>

<font color='green'>
<h2>relativeToLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Adverb</i>. (Objects aligned) relatively to either objects, or the page.</th></thead><tbody>
<tr><td>Default language</td><td>relative to:                                                               </td></tr>
<tr><td>In use since</td><td>2.4                                                                        </td></tr>
<tr><td>Obsolete since</td><td>-                                                                          </td></tr></tbody></table>

<font color='red'>
<h2>rheightLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Height.</th></thead><tbody>
<tr><td>Default language</td><td>height:             </td></tr>
<tr><td>In use since</td><td>2.4                 </td></tr>
<tr><td>Obsolete since</td><td>2.5                 </td></tr></tbody></table>

<font color='red'>
<h2>rwidthLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Width.</th></thead><tbody>
<tr><td>Default language</td><td>width:             </td></tr>
<tr><td>In use since</td><td>2.4                </td></tr>
<tr><td>Obsolete since</td><td>2.5                </td></tr></tbody></table>

<font color='green'>
<h2>seg_type</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the type of a segment.</th></thead><tbody>
<tr><td>Default language</td><td>Change Segment type                          </td></tr>
<tr><td>In use since</td><td>2.4                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                            </td></tr></tbody></table>

<font color='green'>
<h2>selLayerLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To move elements to (another layer):</th></thead><tbody>
<tr><td>Default language</td><td>Move elements to:                                </td></tr>
<tr><td>In use since</td><td>2.4                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                </td></tr></tbody></table>

<font color='green'>
<h2>selLayerNames</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To move selected elements to a different layer.</th></thead><tbody>
<tr><td>Default language</td><td>Move selected elements to a different layer                 </td></tr>
<tr><td>In use since</td><td>2.4                                                         </td></tr>
<tr><td>Obsolete since</td><td>-                                                           </td></tr></tbody></table>

<font color='green'>
<h2>selectedPredefined</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To select predifined values, for the canvas dimensions.</th></thead><tbody>
<tr><td>Default language</td><td>Select predefined:                                                  </td></tr>
<tr><td>In use since</td><td>2.4                                                                 </td></tr>
<tr><td>Obsolete since</td><td>-                                                                   </td></tr></tbody></table>

<font color='green'>
<h2>selected_objects</h2>
</font>
<table><thead><th>Description</th><th><i>Past participle</i>. Objects which are selected. </th></thead><tbody>
<tr><td>Default language</td><td>selected objects                                    </td></tr>
<tr><td>In use since</td><td>2.4                                                 </td></tr>
<tr><td>Obsolete since</td><td>-                                                   </td></tr></tbody></table>

<font color='green'>
<h2>selected_x</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the horizontal coordinate X.</th></thead><tbody>
<tr><td>Default language</td><td>Change X coordinate                                </td></tr>
<tr><td>In use since</td><td>2.4                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                  </td></tr></tbody></table>

<font color='green'>
<h2>selected_y</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the vertical coordinate Y.</th></thead><tbody>
<tr><td>Default language</td><td>Change Y coordinate                              </td></tr>
<tr><td>In use since</td><td>2.4                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                </td></tr></tbody></table>

<font color='green'>
<h2>smallest_object</h2>
</font>
<table><thead><th>Description</th><th><i>Superlative adjective</i>. The smallest object.</th></thead><tbody>
<tr><td>Default language</td><td>smallest object                                   </td></tr>
<tr><td>In use since</td><td>2.4                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                 </td></tr></tbody></table>

<font color='green'>
<h2>straight_segments</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Type of segment: straight line, as opposed to curve.</th></thead><tbody>
<tr><td>Default language</td><td>Straight                                                         </td></tr>
<tr><td>In use since</td><td>2.4                                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                                </td></tr></tbody></table>

<font color='green'>
<h2>stroke_color</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the color of the outline (exterior) of an element.</th></thead><tbody>
<tr><td>Default language</td><td>Change stroke color                                                      </td></tr>
<tr><td>In use since</td><td>2.4                                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                                        </td></tr></tbody></table>

<font color='green'>
<h2>stroke_style</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the style of dashes, for the outline (exterior) of an element.</th></thead><tbody>
<tr><td>Default language</td><td>Change stroke dash style                                                             </td></tr>
<tr><td>In use since</td><td>2.4                                                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                    </td></tr></tbody></table>

<font color='red'>
<h2>stroke_tool_bottom</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The outline (exterior) of an element. This includes the color/opacity, the line thicknes and the line style (dashes and/or dots).</th></thead><tbody>
<tr><td>Default language</td><td>stroke:                                                                                                                                       </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                                           </td></tr>
<tr><td>Obsolete since</td><td>2.5                                                                                                                                           </td></tr></tbody></table>

<font color='green'>
<h2>stroke_width</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the width of the outline (exterior) of an element.</th></thead><tbody>
<tr><td>Default language</td><td>Change stroke width by 1, shift-click to change by 0.1                   </td></tr>
<tr><td>In use since</td><td>2.4                                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                                        </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_bg_note</h2>
</font>
<table><thead><th>Description</th><th>Note : Background will not be saved with the image.</th></thead><tbody>
<tr><td>Default language</td><td>Note: Background will not be saved with image.     </td></tr>
<tr><td>In use since</td><td>2.4                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                  </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_change_background</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The background color or image of the editor.</th></thead><tbody>
<tr><td>Default language</td><td>Editor Background                                        </td></tr>
<tr><td>In use since</td><td>2.4                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                        </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_dim</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The dimensions of the canvas.</th></thead><tbody>
<tr><td>Default language</td><td>Canvas Dimensions                         </td></tr>
<tr><td>In use since</td><td>2.4                                       </td></tr>
<tr><td>Obsolete since</td><td>-                                         </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_editor_prefs</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The preferences of the editor.</th></thead><tbody>
<tr><td>Default language</td><td>Editor Preferences                         </td></tr>
<tr><td>In use since</td><td>2.4                                        </td></tr>
<tr><td>Obsolete since</td><td>-                                          </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_height</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Height.</th></thead><tbody>
<tr><td>Default language</td><td>Height:             </td></tr>
<tr><td>In use since</td><td>2.4                 </td></tr>
<tr><td>Obsolete since</td><td>-                   </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_icons</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Size of the icons.</th></thead><tbody>
<tr><td>Default language</td><td>Icon size                      </td></tr>
<tr><td>In use since</td><td>2.4                            </td></tr>
<tr><td>Obsolete since</td><td>-                              </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_image_props</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The properties of the image.</th></thead><tbody>
<tr><td>Default language</td><td>Image Properties                         </td></tr>
<tr><td>In use since</td><td>2.4                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                        </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_lang</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Language (of the editor).</th></thead><tbody>
<tr><td>Default language</td><td>Language                              </td></tr>
<tr><td>In use since</td><td>2.4                                   </td></tr>
<tr><td>Obsolete since</td><td>-                                     </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_title</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Title (of the image).</th></thead><tbody>
<tr><td>Default language</td><td>Title                             </td></tr>
<tr><td>In use since</td><td>2.4                               </td></tr>
<tr><td>Obsolete since</td><td>-                                 </td></tr></tbody></table>

<font color='green'>
<h2>svginfo_width</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Width (of the image).</th></thead><tbody>
<tr><td>Default language</td><td>Width:                            </td></tr>
<tr><td>In use since</td><td>2.4                               </td></tr>
<tr><td>Obsolete since</td><td>-                                 </td></tr></tbody></table>

<font color='green'>
<h2>text</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Text, content of a text element.</th></thead><tbody>
<tr><td>Default language</td><td>Change text contents                         </td></tr>
<tr><td>In use since</td><td>2.4                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                            </td></tr></tbody></table>

<font color='blue'>
<h2>toggle_stroke_tools</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To show/hide the additional stroke tools</th></thead><tbody>
<tr><td>Default language</td><td>Show/hide more stroke tools                          </td></tr>
<tr><td>In use since</td><td>2.5                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                    </td></tr></tbody></table>

<font color='green'>
<h2>tool_alignbottom</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To align the bottom of selected elements.</th></thead><tbody>
<tr><td>Default language</td><td>Align Bottom                                          </td></tr>
<tr><td>In use since</td><td>2.4                                                   </td></tr>
<tr><td>Obsolete since</td><td>-                                                     </td></tr></tbody></table>

<font color='green'>
<h2>tool_aligncenter</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To center vertically, relatively to the vertical axis</th></thead><tbody>
<tr><td>Default language</td><td>Align Center                                                      </td></tr>
<tr><td>In use since</td><td>2.4                                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                                 </td></tr></tbody></table>

<font color='green'>
<h2>tool_alignleft</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To align the left sides of selected elements.</th></thead><tbody>
<tr><td>Default language</td><td>Align Left                                                </td></tr>
<tr><td>In use since</td><td>2.4                                                       </td></tr>
<tr><td>Obsolete since</td><td>-                                                         </td></tr></tbody></table>

<font color='green'>
<h2>tool_alignmiddle</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To center horizontally, relatively to the horizontal axis</th></thead><tbody>
<tr><td>Default language</td><td>Align Middle                                                          </td></tr>
<tr><td>In use since</td><td>2.4                                                                   </td></tr>
<tr><td>Obsolete since</td><td>-                                                                     </td></tr></tbody></table>

<font color='green'>
<h2>tool_alignright</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To align the right sides of selected elements.</th></thead><tbody>
<tr><td>Default language</td><td>Align Right                                                </td></tr>
<tr><td>In use since</td><td>2.4                                                        </td></tr>
<tr><td>Obsolete since</td><td>-                                                          </td></tr></tbody></table>

<font color='green'>
<h2>tool_aligntop</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To align the top sides of selected elements.</th></thead><tbody>
<tr><td>Default language</td><td>Align Top                                                </td></tr>
<tr><td>In use since</td><td>2.4                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                        </td></tr></tbody></table>

<font color='Green'>
<h2>tool_angle (was: angle)</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the angle of rotation applied to an object.</th></thead><tbody>
<tr><td>Default language</td><td>Change rotation angle                                             </td></tr>
<tr><td>In use since</td><td>2.4                                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                                 </td></tr></tbody></table>

<font color='Green'>
<h2>tool_blur</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the gaussian blur value of an object.</th></thead><tbody>
<tr><td>Default language</td><td>Change gaussian blur value                                  </td></tr>
<tr><td>In use since</td><td>2.5                                                         </td></tr>
<tr><td>Obsolete since</td><td>-                                                           </td></tr></tbody></table>

<font color='green'>
<h2>tool_bold</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective</i>. Bold text</th></thead><tbody>
<tr><td>Default language</td><td>Bold Text                  </td></tr>
<tr><td>In use since</td><td>2.4                        </td></tr>
<tr><td>Obsolete since</td><td>-                          </td></tr></tbody></table>

<font color='green'>
<h2>tool_circle</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Circle.</th></thead><tbody>
<tr><td>Default language</td><td>Circle              </td></tr>
<tr><td>In use since</td><td>2.4                 </td></tr>
<tr><td>Obsolete since</td><td>-                   </td></tr></tbody></table>

<font color='green'>
<h2>tool_clear</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective</i>. New Image</th></thead><tbody>
<tr><td>Default language</td><td>New Image                  </td></tr>
<tr><td>In use since</td><td>2.4                        </td></tr>
<tr><td>Obsolete since</td><td>-                          </td></tr></tbody></table>

<font color='green'>
<h2>tool_clone</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To clone an element</th></thead><tbody>
<tr><td>Default language</td><td>Clone Element                   </td></tr>
<tr><td>In use since</td><td>2.4                             </td></tr>
<tr><td>Obsolete since</td><td>-                               </td></tr></tbody></table>

<font color='green'>
<h2>tool_clone_multi</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To clone elements</th></thead><tbody>
<tr><td>Default language</td><td>Clone Elements                </td></tr>
<tr><td>In use since</td><td>2.4                           </td></tr>
<tr><td>Obsolete since</td><td>-                             </td></tr></tbody></table>

<font color='green'>
<h2>tool_delete</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To delete an element</th></thead><tbody>
<tr><td>Default language</td><td>Delete Element                   </td></tr>
<tr><td>In use since</td><td>2.4                              </td></tr>
<tr><td>Obsolete since</td><td>-                                </td></tr></tbody></table>

<font color='green'>
<h2>tool_delete_multi</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To delete selected elements</th></thead><tbody>
<tr><td>Default language</td><td>Delete Selected Elements                </td></tr>
<tr><td>In use since</td><td>2.4                                     </td></tr>
<tr><td>Obsolete since</td><td>-                                       </td></tr></tbody></table>

<font color='green'>
<h2>tool_docprops</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. The document properties</th></thead><tbody>
<tr><td>Default language</td><td>Document Properties                 </td></tr>
<tr><td>In use since</td><td>2.4                                 </td></tr>
<tr><td>Obsolete since</td><td>-                                   </td></tr></tbody></table>

<font color='green'>
<h2>tool_docprops_cancel</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To cancel</th></thead><tbody>
<tr><td>Default language</td><td>Cancel                </td></tr>
<tr><td>In use since</td><td>2.4                   </td></tr>
<tr><td>Obsolete since</td><td>-                     </td></tr></tbody></table>

<font color='green'>
<h2>tool_docprops_save</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. OK <b>(does not mean "Save")</b></th></thead><tbody>
<tr><td>Default language</td><td>OK                                           </td></tr>
<tr><td>In use since</td><td>2.4                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                            </td></tr></tbody></table>

<font color='green'>
<h2>tool_ellipse</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Ellipse</th></thead><tbody>
<tr><td>Default language</td><td>Ellipse             </td></tr>
<tr><td>In use since</td><td>2.4                 </td></tr>
<tr><td>Obsolete since</td><td>-                   </td></tr></tbody></table>

<font color='blue'>
<h2>tool_export</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To save the image as a PNG, JPEG, BMP, or WEBP file</th></thead><tbody>
<tr><td>Default language</td><td>Export                                                          </td></tr>
<tr><td>In use since</td><td>2.5                                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                                               </td></tr></tbody></table>

<font color='blue'>
<h2>tool_eyedropper</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. Tool for copying the style from one element to another</th></thead><tbody>
<tr><td>Default language</td><td>Eye Dropper Tool                                                   </td></tr>
<tr><td>In use since</td><td>2.5                                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                                  </td></tr></tbody></table>

<font color='green'>
<h2>tool_fhellipse</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Free-hand ellipse</th></thead><tbody>
<tr><td>Default language</td><td>Free-Hand Ellipse             </td></tr>
<tr><td>In use since</td><td>2.4                           </td></tr>
<tr><td>Obsolete since</td><td>-                             </td></tr></tbody></table>

<font color='green'>
<h2>tool_fhpath</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Pencil tool</th></thead><tbody>
<tr><td>Default language</td><td>Pencil Tool             </td></tr>
<tr><td>In use since</td><td>2.4                     </td></tr>
<tr><td>Obsolete since</td><td>-                       </td></tr></tbody></table>

<font color='green'>
<h2>tool_fhrect</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Free-hand rectangle</th></thead><tbody>
<tr><td>Default language</td><td>Free-Hand Rectangle             </td></tr>
<tr><td>In use since</td><td>2.4                             </td></tr>
<tr><td>Obsolete since</td><td>-                               </td></tr></tbody></table>

<font color='Green'>
<h2>tool_font_size (was: font_size)</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the font size of a text element.</th></thead><tbody>
<tr><td>Default language</td><td>Change Font Size                                       </td></tr>
<tr><td>In use since</td><td>2.4                                                    </td></tr>
<tr><td>Obsolete since</td><td>-                                                      </td></tr></tbody></table>

<font color='green'>
<h2>tool_group</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To group elements</th></thead><tbody>
<tr><td>Default language</td><td>Group Elements                </td></tr>
<tr><td>In use since</td><td>2.4                           </td></tr>
<tr><td>Obsolete since</td><td>-                             </td></tr></tbody></table>

<font color='green'>
<h2>tool_image</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Image tool</th></thead><tbody>
<tr><td>Default language</td><td>Image Tool             </td></tr>
<tr><td>In use since</td><td>2.4                    </td></tr>
<tr><td>Obsolete since</td><td>-                      </td></tr></tbody></table>

<font color='blue'>
<h2>tool_import</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To import an SVG file into the image.</th></thead><tbody>
<tr><td>Default language</td><td>Import SVG                                        </td></tr>
<tr><td>In use since</td><td>2.5                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                 </td></tr></tbody></table>

<font color='Green'>
<h2>tool_opacity (was: group_opacity)</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the opacity of selected items.</th></thead><tbody>
<tr><td>Default language</td><td>Change selected item opacity                         </td></tr>
<tr><td>In use since</td><td>2.4                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                    </td></tr></tbody></table>

<font color='blue'>
<h2>tool_openclose_path</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To make a path or part of a path open or closed</th></thead><tbody>
<tr><td>Default language</td><td>Open/close sub-path                                         </td></tr>
<tr><td>In use since</td><td>2.5                                                         </td></tr>
<tr><td>Obsolete since</td><td>-                                                           </td></tr></tbody></table>

<font color='green'>
<h2>tool_italic</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective</i>. Italic text</th></thead><tbody>
<tr><td>Default language</td><td>Italic Text                  </td></tr>
<tr><td>In use since</td><td>2.4                          </td></tr>
<tr><td>Obsolete since</td><td>-                            </td></tr></tbody></table>

<font color='green'>
<h2>tool_line</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Line tool</th></thead><tbody>
<tr><td>Default language</td><td>Line Tool             </td></tr>
<tr><td>In use since</td><td>2.4                   </td></tr>
<tr><td>Obsolete since</td><td>-                     </td></tr></tbody></table>

<font color='green'>
<h2>tool_move_bottom</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To move (the selected element) to the bottom</th></thead><tbody>
<tr><td>Default language</td><td>Move to Bottom                                           </td></tr>
<tr><td>In use since</td><td>2.4                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                        </td></tr></tbody></table>

<font color='green'>
<h2>tool_move_top</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To move (the selected element) to the top</th></thead><tbody>
<tr><td>Default language</td><td>Move to Top                                           </td></tr>
<tr><td>In use since</td><td>2.4                                                   </td></tr>
<tr><td>Obsolete since</td><td>-                                                     </td></tr></tbody></table>

<font color='green'>
<h2>tool_node_clone</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To clone a node</th></thead><tbody>
<tr><td>Default language</td><td>Clone Node                  </td></tr>
<tr><td>In use since</td><td>2.4                         </td></tr>
<tr><td>Obsolete since</td><td>-                           </td></tr></tbody></table>

<font color='green'>
<h2>tool_node_delete</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To delete a node</th></thead><tbody>
<tr><td>Default language</td><td>Delete Node                  </td></tr>
<tr><td>In use since</td><td>2.4                          </td></tr>
<tr><td>Obsolete since</td><td>-                            </td></tr></tbody></table>

<font color='green'>
<h2>tool_node_link</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To link control points: to make the two handles of a node move together, with solidarity, instead of individually.</th></thead><tbody>
<tr><td>Default language</td><td>Link Control Points                                                                                                            </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                            </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                              </td></tr></tbody></table>

<font color='green'>
<h2>tool_open</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To open an image</th></thead><tbody>
<tr><td>Default language</td><td>Open Image                   </td></tr>
<tr><td>In use since</td><td>2.4                          </td></tr>
<tr><td>Obsolete since</td><td>-                            </td></tr></tbody></table>

<font color='green'>
<h2>tool_path</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Path tool. The chosen word musn't mean Polygon.</th></thead><tbody>
<tr><td>Default language</td><td>Path Tool                                                   </td></tr>
<tr><td>In use since</td><td>2.3                                                         </td></tr>
<tr><td>Obsolete since</td><td>2.4                                                         </td></tr></tbody></table>

<font color='blue'>
<h2>tool_position</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To align a single element in reference to the page</th></thead><tbody>
<tr><td>Default language</td><td>Align Element to Page                                          </td></tr>
<tr><td>In use since</td><td>2.5                                                            </td></tr>
<tr><td>Obsolete since</td><td>-                                                              </td></tr></tbody></table>

<font color='green'>
<h2>tool_rect</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Rectangle</th></thead><tbody>
<tr><td>Default language</td><td>Rectangle             </td></tr>
<tr><td>In use since</td><td>2.4                   </td></tr>
<tr><td>Obsolete since</td><td>-                     </td></tr></tbody></table>

<font color='green'>
<h2>tool_redo</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To redo</th></thead><tbody>
<tr><td>Default language</td><td>Redo                </td></tr>
<tr><td>In use since</td><td>2.4                 </td></tr>
<tr><td>Obsolete since</td><td>-                   </td></tr></tbody></table>

<font color='green'>
<h2>tool_reorient</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. (to) Reorient (a) path: For a previously rotated object, make its bounding box parallel to the canvas, and with a rotation angle of 0°. Resets the bounding box origin.</th></thead><tbody>
<tr><td>Default language</td><td>Reorient path                                                                                                                                                                       </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                                                                                 </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                                                                                   </td></tr></tbody></table>

<font color='green'>
<h2>tool_save</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To save the image</th></thead><tbody>
<tr><td>Default language</td><td>Save Image                    </td></tr>
<tr><td>In use since</td><td>2.4                           </td></tr>
<tr><td>Obsolete since</td><td>-                             </td></tr></tbody></table>

<font color='green'>
<h2>tool_select</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Select (selection) tool</th></thead><tbody>
<tr><td>Default language</td><td>Select Tool                         </td></tr>
<tr><td>In use since</td><td>2.4                                 </td></tr>
<tr><td>Obsolete since</td><td>-                                   </td></tr></tbody></table>

<font color='green'>
<h2>tool_source</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To edit the source (opens the source editor)</th></thead><tbody>
<tr><td>Default language</td><td>Edit Source                                              </td></tr>
<tr><td>In use since</td><td>2.4                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                        </td></tr></tbody></table>

<font color='green'>
<h2>tool_source_cancel</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To cancel, discard changes.</th></thead><tbody>
<tr><td>Default language</td><td>Cancel                                  </td></tr>
<tr><td>In use since</td><td>2.4                                     </td></tr>
<tr><td>Obsolete since</td><td>-                                       </td></tr></tbody></table>

<font color='green'>
<h2>tool_source_save</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. (to) Apply changes, accept changes. <b>(does not mean "Save")</b></th></thead><tbody>
<tr><td>Default language</td><td>Apply Changes                                                                 </td></tr>
<tr><td>In use since</td><td>2.4                                                                           </td></tr>
<tr><td>Obsolete since</td><td>-                                                                             </td></tr></tbody></table>

<font color='green'>
<h2>tool_square</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Square</th></thead><tbody>
<tr><td>Default language</td><td>Square             </td></tr>
<tr><td>In use since</td><td>2.4                </td></tr>
<tr><td>Obsolete since</td><td>-                  </td></tr></tbody></table>

<font color='green'>
<h2>tool_text</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Text tool</th></thead><tbody>
<tr><td>Default language</td><td>Text Tool             </td></tr>
<tr><td>In use since</td><td>2.4                   </td></tr>
<tr><td>Obsolete since</td><td>-                     </td></tr></tbody></table>

<font color='green'>
<h2>tool_topath</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To convert (a regular shape, circle, ellipse, rectangle...) in a path (with editable segments)</th></thead><tbody>
<tr><td>Default language</td><td>Convert to Path                                                                                            </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                        </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                          </td></tr></tbody></table>

<font color='green'>
<h2>tool_undo</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To undo</th></thead><tbody>
<tr><td>Default language</td><td>Undo                </td></tr>
<tr><td>In use since</td><td>2.4                 </td></tr>
<tr><td>Obsolete since</td><td>-                   </td></tr></tbody></table>

<font color='green'>
<h2>tool_ungroup</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To ungroup elements (previously grouped)</th></thead><tbody>
<tr><td>Default language</td><td>Ungroup Elements                                     </td></tr>
<tr><td>In use since</td><td>2.4                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                    </td></tr></tbody></table>

<font color='green'>
<h2>tool_wireframe</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Wireframe, outline mode (shows the outline of the elements, with no colors)</th></thead><tbody>
<tr><td>Default language</td><td>Wireframe Mode                                                                          </td></tr>
<tr><td>In use since</td><td>2.4                                                                                     </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                       </td></tr></tbody></table>

<font color='green'>
<h2>tool_zoom</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Zoom tool</th></thead><tbody>
<tr><td>Default language</td><td>Zoom Tool             </td></tr>
<tr><td>In use since</td><td>2.4                   </td></tr>
<tr><td>Obsolete since</td><td>-                     </td></tr></tbody></table>

<font color='Orange'>
<h2>tools_ellipse_show</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Ellipse/Circle tool</th></thead><tbody>
<tr><td>Default language</td><td>Ellipse/Circle Tool             </td></tr>
<tr><td>In use since</td><td>2.4                             </td></tr>
<tr><td>Obsolete since</td><td>2.5 <a href='https://code.google.com/p/svg-edit/source/detail?r=1333'>r1333</a></td></tr></tbody></table>

<font color='Orange'>
<h2>tools_rect_show</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Square/Rectangle tool</th></thead><tbody>
<tr><td>Default language</td><td>Square/Rect Tool                  </td></tr>
<tr><td>In use since</td><td>2.4                               </td></tr>
<tr><td>Obsolete since</td><td>2.5 <a href='https://code.google.com/p/svg-edit/source/detail?r=1333'>r1333</a></td></tr></tbody></table>

<font color='blue'>
<h2>url_notice</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Notice given to indicate the raster image cannot be embedded and depends on the given path to appear</th></thead><tbody>
<tr><td>Default language</td><td>NOTE: This image cannot be embedded. It will depend on this path to be displayed                                     </td></tr>
<tr><td>In use since</td><td>2.5                                                                                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                    </td></tr></tbody></table>

<font color='blue'>
<h2>zoom_panel (was: zoom)</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. To change the zoom level</th></thead><tbody>
<tr><td>Default language</td><td>Change zoom level                    </td></tr>
<tr><td>In use since</td><td>2.5                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                    </td></tr></tbody></table>

<font color='red'>
<h2>zoomLabel</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Zoom:</th></thead><tbody>
<tr><td>Default language</td><td>zoom:             </td></tr>
<tr><td>In use since</td><td>2.4               </td></tr>
<tr><td>Obsolete since</td><td>2.5               </td></tr></tbody></table>

<font color='green'>
<h2>sidepanel_handle</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>, then <i>Noun</i>. To drag left/right (in order) to resize the side panel, then, L a y e r s.</th></thead><tbody>
<tr><td>Default language</td><td>Drag left/right to resize side panel                                                                     </td></tr>
<tr><td>Default language</td><td>L a y e r s                                                                                              </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                        </td></tr></tbody></table>

<hr />

<h1>JavaScript strings (js_strings)</h1>

<font color='Green'>
<h2>QerrorsRevertToSource</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. States that there were errors while parsing the manually given SVG source code. Asks if it should go back to the original code.</th></thead><tbody>
<tr><td>Default language</td><td>There were parsing errors in your SVG source.\nRevert back to original SVG source?                                                              </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                                               </td></tr></tbody></table>

<font color='Green'>
<h2>QignoreSourceChanges</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Verifies that the changes made to the SVG source code can be rolled back.</th></thead><tbody>
<tr><td>Default language</td><td>Ignore changes made to SVG source?                                                        </td></tr>
<tr><td>In use since</td><td>2.4                                                                                       </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                         </td></tr></tbody></table>

<font color='Green'>
<h2>QmoveElemsToLayer</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Verifies that the selected items must be moved to another (already specified) layer. (<i>'%s' must not be translated or changed.</i>)</th></thead><tbody>
<tr><td>Default language</td><td>Move selected elements to layer '%s'?                                                                                                                 </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                                                   </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                                                     </td></tr></tbody></table>

<font color='Green'>
<h2>QwantToClear</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Verifies if the entire drawing, including the undo history, should be discarded.</th></thead><tbody>
<tr><td>Default language</td><td>Do you want to clear the drawing?\nThis will also erase your undo history!                       </td></tr>
<tr><td>In use since</td><td>2.4                                                                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                </td></tr></tbody></table>

<font color='Green'>
<h2>cancel</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. Cancels a given command and returns back to the state before that.</th></thead><tbody>
<tr><td>Default language</td><td>Cancel                                                                         </td></tr>
<tr><td>In use since</td><td>2.4                                                                            </td></tr>
<tr><td>Obsolete since</td><td>-                                                                              </td></tr></tbody></table>

<font color='Green'>
<h2>dupeLayerName</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Is displayed if a layer is created with a name of an already existing layer.</th></thead><tbody>
<tr><td>Default language</td><td>There is already a layer named that!                                                         </td></tr>
<tr><td>In use since</td><td>2.4                                                                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                            </td></tr></tbody></table>

<font color='Green'>
<h2>enterNewImgURL</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. Lets you edit the URL of an inserted image.</th></thead><tbody>
<tr><td>Default language</td><td>Enter the new image URL                                 </td></tr>
<tr><td>In use since</td><td>2.4                                                     </td></tr>
<tr><td>Obsolete since</td><td>-                                                       </td></tr></tbody></table>

<font color='Green'>
<h2>enterNewLayerName</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Asks for a new layer name. A layer name identifies a layer.</th></thead><tbody>
<tr><td>Default language</td><td>Please enter the new layer name                                             </td></tr>
<tr><td>In use since</td><td>2.4                                                                         </td></tr>
<tr><td>Obsolete since</td><td>-                                                                           </td></tr></tbody></table>

<font color='Green'>
<h2>enterUniqueLayerName</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Asks for a unique layer name.</th></thead><tbody>
<tr><td>Default language</td><td>Please enter a unique layer name              </td></tr>
<tr><td>In use since</td><td>2.4                                           </td></tr>
<tr><td>Obsolete since</td><td>-                                             </td></tr></tbody></table>

<font color='Green'>
<h2>featNotSupported</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. States that a function is not supported.</th></thead><tbody>
<tr><td>Default language</td><td>Feature not supported                                </td></tr>
<tr><td>In use since</td><td>2.4                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                    </td></tr></tbody></table>

<font color='Green'>
<h2>invalidAttrValGiven</h2>
</font>
<table><thead><th>Description</th><th><i>Adjective</i>. States that a given value is not correct. Eg some text is given while a number is required.</th></thead><tbody>
<tr><td>Default language</td><td>Invalid value given                                                                                          </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                            </td></tr></tbody></table>

<font color='Blue'>
<h2>defsFailOnSave</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Provides a message for Firefox users indicating that gradients, markers, etc will not appear as expected when saving. </th></thead><tbody>
<tr><td>Default language</td><td>NOTE: Due to a bug in your browser, this image may appear wrong (missing gradients or elements). It will however appear correct once actually saved.</td></tr>
<tr><td>In use since</td><td>2.5                                                                                                                                    </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                                      </td></tr></tbody></table>

<font color='Blue'>
<h2>loadingImage</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Text that briefly appears on the page when the "Export" option is chosen</th></thead><tbody>
<tr><td>Default language</td><td>Loading image, please wait...                                                            </td></tr>
<tr><td>In use since</td><td>2.5                                                                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                        </td></tr></tbody></table>

<font color='Blue'>
<h2>saveFromBrowser</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Text that appears in popup on the new window with a SVG or image (%s = PNG, JPEG, BMP, WEBP, SVG)</th></thead><tbody>
<tr><td>Default language</td><td>Select \"Save As...\" in your browser to save this image as a %s file.                                            </td></tr>
<tr><td>In use since</td><td>2.5                                                                                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                 </td></tr></tbody></table>

<font color='Blue'>
<h2>noteTheseIssues</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. On "Export", the prefix text to indicate there are issues. </th></thead><tbody>
<tr><td>Default language</td><td>Also note the following issues:                                             </td></tr>
<tr><td>In use since</td><td>2.5                                                                         </td></tr>
<tr><td>Obsolete since</td><td>-                                                                           </td></tr></tbody></table>

<font color='Green'>
<h2>key_backspace</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Name of the keyboard key: backspace</th></thead><tbody>
<tr><td>Default language</td><td>backspace                                       </td></tr>
<tr><td>In use since</td><td>2.4                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                               </td></tr></tbody></table>

<font color='Green'>
<h2>key_del</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Name of the keyboard key: delete</th></thead><tbody>
<tr><td>Default language</td><td>delete                                       </td></tr>
<tr><td>In use since</td><td>2.4                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                            </td></tr></tbody></table>

<font color='Green'>
<h2>key_down</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Name of the keyboard key: down</th></thead><tbody>
<tr><td>Default language</td><td>down                                       </td></tr>
<tr><td>In use since</td><td>2.4                                        </td></tr>
<tr><td>Obsolete since</td><td>-                                          </td></tr></tbody></table>

<font color='Green'>
<h2>key_up</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Name of the keyboard key: up</th></thead><tbody>
<tr><td>Default language</td><td>up                                       </td></tr>
<tr><td>In use since</td><td>2.4                                      </td></tr>
<tr><td>Obsolete since</td><td>-                                        </td></tr></tbody></table>

<font color='Green'>
<h2>layer</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Gives the name for a layer. An image can have multiple layers that can group a number of elements.</th></thead><tbody>
<tr><td>Default language</td><td>Layer                                                                                                          </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                            </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                              </td></tr></tbody></table>

<font color='Green'>
<h2>layerHasThatName</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. States that the new layer name is the same as the old layer name.</th></thead><tbody>
<tr><td>Default language</td><td>Layer already has that name                                                       </td></tr>
<tr><td>In use since</td><td>2.4                                                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                 </td></tr></tbody></table>

<font color='Green'>
<h2>noContentToFitTo</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. States that the command to resize the canvas to all content could not be executed, because there is no content.</th></thead><tbody>
<tr><td>Default language</td><td>No content to fit to                                                                                                            </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                             </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                               </td></tr></tbody></table>

<font color='Green'>
<h2>ok</h2>
</font>
<table><thead><th>Description</th><th><i>Noun</i>. Executes the action and commits the changes that have been made.</th></thead><tbody>
<tr><td>Default language</td><td>OK                                                                           </td></tr>
<tr><td>In use since</td><td>2.4                                                                          </td></tr>
<tr><td>Obsolete since</td><td>-                                                                            </td></tr></tbody></table>

<font color='Green'>
<h2>pathCtrlPtTooltip</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. States that the point that is being hovered can be dragged elsewhere. This will change the curve of the matching line.</th></thead><tbody>
<tr><td>Default language</td><td>Drag control point to adjust curve properties                                                                                      </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                                </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                                  </td></tr></tbody></table>

<font color='Green'>
<h2>pathNodeTooltip</h2>
</font>
<table><thead><th>Description</th><th><i>Verb</i>. States that the point that is being hovered can be dragged elsewhere. This will change the shape. The point can also be double-clicked, which will change the matching line type.</th></thead><tbody>
<tr><td>Default language</td><td>Drag node to move it. Double-click node to change segment type                                                                                                                                </td></tr>
<tr><td>In use since</td><td>2.4                                                                                                                                                                                           </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                                                                                             </td></tr></tbody></table>

<font color='Blue'>
<h2>exportNoBlur</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Note that blur is not supported on image export </th></thead><tbody>
<tr><td>Default language</td><td>Blurred elements will appear as un-blurred                       </td></tr>
<tr><td>In use since</td><td>2.5                                                              </td></tr>
<tr><td>Obsolete since</td><td>-                                                                </td></tr></tbody></table>

<font color='Blue'>
<h2>exportNoImage</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Note that Image elements are not supported on image export </th></thead><tbody>
<tr><td>Default language</td><td>Image elements will not appear                                              </td></tr>
<tr><td>In use since</td><td>2.5                                                                         </td></tr>
<tr><td>Obsolete since</td><td>-                                                                           </td></tr></tbody></table>

<font color='Blue'>
<h2>exportNoforeignObject</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Note that foreignObject elements are not supported on image export </th></thead><tbody>
<tr><td>Default language</td><td>foreignObject elements will not appear                                              </td></tr>
<tr><td>In use since</td><td>2.5                                                                                 </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                   </td></tr></tbody></table>

<font color='Blue'>
<h2>exportNoDashArray</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Note that stroke-dasharray is not supported on image export (will appear as regular stroke instead) </th></thead><tbody>
<tr><td>Default language</td><td>Strokes will appear filled                                                                                           </td></tr>
<tr><td>In use since</td><td>2.5                                                                                                                  </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                    </td></tr></tbody></table>

<font color='Blue'>
<h2>exportNoText</h2>
</font>
<table><thead><th>Description</th><th><i>Sentence</i>. Note that text is not supported on image export (will only appear in browsers that don't support Canvas Text API)</th></thead><tbody>
<tr><td>Default language</td><td>Text may not appear as expected                                                                                                   </td></tr>
<tr><td>In use since</td><td>2.5                                                                                                                               </td></tr>
<tr><td>Obsolete since</td><td>-                                                                                                                                 </td></tr></tbody></table>

<hr />