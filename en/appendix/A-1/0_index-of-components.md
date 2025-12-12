# Index

### 2.1. Index

\#####This index provides additional information on all the components used in this primer, as well as other components you might find useful. This is just an introduction to over 500 components in the Grasshopper plugin.

### Parameters

\####Geometry

|              |                                                                                                                                                          |                                                |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| P.G.Crv      | <p>Curve Parameter<br>Represents a collection of Curve geometry. Curve geometry is the common denominator of all curve types in Grasshopper.</p>         | ![IMAGE](../../.gitbook/assets/PGCrv.png)      |
| P.G.Circle   | <p>Circle Parameter<br>Represents a collection of Circle primitives.</p>                                                                                 | ![IMAGE](../../.gitbook/assets/PGCircle.png)   |
| P.G.Geo      | <p>Geometry Parameter<br>Represents a collection of 3D Geometry.</p>                                                                                     | ![IMAGE](../../.gitbook/assets/PGGeo.png)      |
| P.G.Pipeline | <p>Geometry Pipeline<br>Defines a geometry pipeline from Rhino to Grasshopper.</p>                                                                       | ![IMAGE](../../.gitbook/assets/PGPipeline.png) |
| P.G.Pt       | <p>Point Parameter<br>Point parameters are capable of storing persistent data. You can set the persistent records through the parameter menu.</p>        | ![IMAGE](../../.gitbook/assets/PGPt.png)       |
| P.G.Srf      | <p>Surface Parameter<br>Represents a collection of Surface geometry. Surface geometry is the common denominator of all surface types in Grasshopper.</p> | ![IMAGE](../../.gitbook/assets/PGSrf.png)      |

\####Primitive

|          |                                                                                                                                                                                                                                                                                                           |                                            |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| P.P.Bool | <p>Boolean Parameter<br>Represents a collection of Boolean (True/False) values.</p>                                                                                                                                                                                                                       | ![IMAGE](../../.gitbook/assets/PPBool.png) |
| P.P.D    | <p>Domain Parameter<br>Represents a collection of one-dimensional Domains. Domains are typically used to represent curve fragments and continuous numeric ranges. A domain consists of two numbers that indicate the limits of the domain, everything in between these numbers is part of the domain.</p> | ![IMAGE](../../.gitbook/assets/PPD.png)    |
| P.P.D2   | <p>Domain<sup>2</sup> Parameter<br>Contains a collection of two-dimensional domains. 2D Domains are typically used to represent surface fragments. A two-dimensional domain consists of two one-dimensional domains.</p>                                                                                  | ![IMAGE](../../.gitbook/assets/PPD2.png)   |
| P.P.ID   | <p>Guid Parameter<br>Represents a collection of Globally Unique Identifiers. Guid parameters are capable of storing persistent data. You can set the persistent records through the parameter menu.</p>                                                                                                   | ![IMAGE](../../.gitbook/assets/PPID.png)   |
| P.P.Int  | <p>Integer Parameter<br>Represents a collection of Integer numeric values. Integer parameters are capable of storing persistent data. You can set the persistent records through the parameter menu.</p>                                                                                                  | ![IMAGE](../../.gitbook/assets/PPInt.png)  |
| P.P.Num  | <p>Number Parameter<br>Represents a collection of floating point values. Number parameters are capable of storing persistent data. You can set the persistent records through the parameter menu.</p>                                                                                                     | ![IMAGE](../../.gitbook/assets/PPNum.png)  |
| P.P.Path | <p>File Path<br>Contains a collection of file paths.</p>                                                                                                                                                                                                                                                  | ![IMAGE](../../.gitbook/assets/PPPath.png) |

\####Input

|            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |                                              |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| P.I.Toggle | <p>Boolean Toggle<br>Boolean (true/false) toggle.</p>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | ![IMAGE](../../.gitbook/assets/PIToggle.png) |
| P.I.Button | <p>Button<br>Button object with two values. When pressed, the button object returns a true value and then resets to false.</p>                                                                                                                                                                                                                                                                                                                                                                                                              | ![IMAGE](../../.gitbook/assets/PIButton.png) |
| P.I.Swatch | <p>Color Swatch<br>A swatch is a special interface object that allows for quick setting of individual color values. You can change the color of a swatch through the context menu.</p>                                                                                                                                                                                                                                                                                                                                                      | ![IMAGE](../../.gitbook/assets/PISwatch.png) |
| P.I.Grad   | <p>Gradient Control<br>Gradient controls allow you to define a color gradient within a numeric domain. By default the unit domain (0.0 ~ 1.0) is used, but this can be adjusted via the L0 and L1 input parameters. You can add color grips to the gradient object by dragging from the color wheel at the upper left and set color grips by right clicking them.</p>                                                                                                                                                                       | ![IMAGE](../../.gitbook/assets/PIGrad.png)   |
| P.I.Graph  | <p>Graph Mapper<br>Graph mapper objects allow you to remap a set of numbers. By default the {x} and {y} domains of a graph function are unit domains (0.0 ~ 1.0), but these can be adjusted via the Graph Editor. Graph mappers can contain a single mapping function, which can be picked through the context menu. Graphs typically have grips (little circles), which can be used to modify the variables that define the graph equation. By default, a graph mapper objects contains no graph and performs a 1:1 mapping of values.</p> | ![IMAGE](../../.gitbook/assets/PIGraph.png)  |
| P.I.Slider | <p>Number Slider<br>A slider is a special interface object that allows for quick setting of individual numeric values. You can change the values and properties through the menu, or by double-clicking a slider object. Sliders can be made longer or shorter by dragging the rightmost edge left or right. Note that sliders only have an output (ie. no input).</p>                                                                                                                                                                      | ![IMAGE](../../.gitbook/assets/PISlider.png) |
| P.I.Panel  | <p>Panel<br>A panel for custom notes and text values. It is typically an inactive object that allows you to add remarks or explanations to a Document. Panels can also receive their information from elsewhere. If you plug an output parameter into a Panel, you can see the contents of that parameter in real-time. All data in Grasshopper can be viewed in this way. Panels can also stream their content to a text file.</p>                                                                                                         | ![IMAGE](../../.gitbook/assets/PIPanel.png)  |
| P.I.List   | <p>Value List<br>Provides a list of preset values from which to choose.</p>                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | ![IMAGE](../../.gitbook/assets/PIList.png)   |

\####Utilities

|              |                                                                |                                                |
| ------------ | -------------------------------------------------------------- | ---------------------------------------------- |
| P.U.Cin      | <p>Cluster Input<br>Represents a cluster input parameter.</p>  | ![IMAGE](../../.gitbook/assets/PUCin.png)      |
| P.U.COut     | <p>Cluster Output<br>Represents a cluster input parameter.</p> | ![IMAGE](../../.gitbook/assets/PUCOut.png)     |
| P.U.Dam      | <p>Data Dam<br>Delay data on its way through the document.</p> | ![IMAGE](../../.gitbook/assets/PUDam.png)      |
| P.U.Jump     | <p>Jump<br>Jump between different locations.</p>               | ![IMAGE](../../.gitbook/assets/PUJump.png)     |
| P.U.Viewer   | <p>Param Viewer<br>A viewer for data structures.</p>           | ![IMAGE](../../.gitbook/assets/PUViewer.png)   |
| P.U.Scribble | <p>Scribble<br>A quick note.</p>                               | ![IMAGE](../../.gitbook/assets/PUScribble.png) |

### Maths

\####Domain

|               |                                                                                       |                                                 |
| ------------- | ------------------------------------------------------------------------------------- | ----------------------------------------------- |
| M.D.Bnd       | <p>Bounds<br>Create a numeric domain which encompasses a list of numbers.</p>         | ![IMAGE](../../.gitbook/assets/MDBnd.png)       |
| M.D.Consec    | <p>Consecutive Domains<br>Create consecutive domains from a list of numbers.</p>      | ![IMAGE](../../.gitbook/assets/MDConsec.png)    |
| M.D.Dom       | <p>Construct Domain<br>Create a numeric domain from two numeric extremes.</p>         | ![IMAGE](../../.gitbook/assets/MDDom.png)       |
| M.D.Dom2Num   | <p>Construct Domain²<br>Create a two-dimensional domain from four numbers.</p>        | ![IMAGE](../../.gitbook/assets/MDDom2Num.png)   |
| M.D.DeDomain  | <p>Deconstruct Domain<br>Deconstruct a numeric domain into its component parts.</p>   | ![IMAGE](../../.gitbook/assets/MDDeDomain.png)  |
| M.D.DeDom2Num | <p>Deconstruct Domain²<br>Deconstruct a two-dimensional domain into four numbers.</p> | ![IMAGE](../../.gitbook/assets/MDDeDom2Num.png) |
| M.D.Divide    | <p>Divide Domain²<br>Divides a two-dimensional domain into equal segments.</p>        | ![IMAGE](../../.gitbook/assets/MDDivide.png)    |
| M.D.Inc       | <p>Includes<br>Test a numeric value to see if it is included in the domain.</p>       | ![IMAGE](../../.gitbook/assets/MDInc.png)       |
| M.D.ReMap     | <p>Remap Numbers<br>Remap numbers into a new numeric domain.</p>                      | ![IMAGE](../../.gitbook/assets/MDReMap.png)     |

\####Operators

|              |                                                                                                                        |                                                |
| ------------ | ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| M.O.Add      | <p>Addition<br>Mathematical addition.</p>                                                                              | ![IMAGE](../../.gitbook/assets/MOAdd.png)      |
| M.O.Div      | <p>Division<br>Mathematical division.</p>                                                                              | ![IMAGE](../../.gitbook/assets/MODiv.png)      |
| M.O.Equals   | <p>Equality<br>Test for (in)equality of two numbers.</p>                                                               | ![IMAGE](../../.gitbook/assets/MOEquals.png)   |
| M.O.And      | <p>Gate And<br>Perform boolean conjunction (AND gate). Both inputs need to be True for the result to be True.</p>      | ![IMAGE](../../.gitbook/assets/MOAnd.png)      |
| M.O.Not      | <p>Gate Not<br>Perform boolean negation (NOT gate).</p>                                                                | ![IMAGE](../../.gitbook/assets/MONot.png)      |
| M.O.Or       | <p>Gate Or<br>Perform boolean disjunction (OR gate). Only a single input has to be True for the result to be True.</p> | ![IMAGE](../../.gitbook/assets/MOOr.png)       |
| M.O.Larger   | <p>Larger Than<br>Larger than (or equal to).</p>                                                                       | ![IMAGE](../../.gitbook/assets/MOLarger.png)   |
| M.O.Multiply | <p>Multiplication<br>Mathematical multiplication.</p>                                                                  | ![IMAGE](../../.gitbook/assets/MOMultiply.png) |
| M.O.Smaller  | <p>Smaller Than<br>Larger than (or equal to).</p>                                                                      | ![IMAGE](../../.gitbook/assets/MOSmaller.png)  |
| M.O.Similar  | <p>Similarity<br>Test for similarity of two numbers.</p>                                                               | ![IMAGE](../../.gitbook/assets/MOSimilar.png)  |
| M.O.Sub      | <p>Subtraction<br>Mathematical subtraction.</p>                                                                        | ![IMAGE](../../.gitbook/assets/MOSub.png)      |

\####Script

|                |                                                                                |                                                  |
| -------------- | ------------------------------------------------------------------------------ | ------------------------------------------------ |
| M.S.Eval       | <p>Evaluate<br>Evaluate an expression with a flexible number of variables.</p> | ![IMAGE](../../.gitbook/assets/MSEval.png)       |
| M.S.Expression | <p>Expression<br>Evaluate an expression.</p>                                   | ![IMAGE](../../.gitbook/assets/MSExpression.png) |

\####Trig

|         |                                                                     |                                           |
| ------- | ------------------------------------------------------------------- | ----------------------------------------- |
| M.T.Cos | <p>Cosine<br>Compute the cosine of a value.</p>                     | ![IMAGE](../../.gitbook/assets/MTCos.png) |
| M.T.Deg | <p>Degrees<br>Convert an angle specified in radians to degrees.</p> | ![IMAGE](../../.gitbook/assets/MTDeg.png) |
| M.T.Rad | <p>Radians<br>Convert an angle specified in degrees to radians.</p> | ![IMAGE](../../.gitbook/assets/MTRad.png) |
| M.T.Sin | <p>Sine<br>Compute the sine of a value.</p>                         | ![IMAGE](../../.gitbook/assets/MTSin.png) |

\####Utilities

|         |                                                                      |                                           |
| ------- | -------------------------------------------------------------------- | ----------------------------------------- |
| M.U.Avr | <p>Average<br>Solve the arithmetic average for a set of items.</p>   | ![IMAGE](../../.gitbook/assets/MUAvr.png) |
| M.U.Phi | <p>Golden Ratio<br>Returns a multiple of the golden ratio (Phi).</p> | ![IMAGE](../../.gitbook/assets/MUPhi.png) |
| M.U.Pi  | <p>Pi<br>Returns a multiple of Pi.</p>                               | ![IMAGE](../../.gitbook/assets/MUPi.png)  |

### Sets

\####List

|              |                                                                                                                                                                                                                                                                                                                         |                                                |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| S.L.Combine  | <p>Combine Data<br>Combine non-null items out of several inputs.</p>                                                                                                                                                                                                                                                    | ![IMAGE](../../.gitbook/assets/SLCombine.png)  |
| S.L.CrossRef | <p>Cross Reference<br>Cross Reference data from multiple lists.</p>                                                                                                                                                                                                                                                     | ![IMAGE](../../.gitbook/assets/SLCrossRef.png) |
| S.L.Dispatch | <p>Dispatch<br>Dispatch the items in a list into two target lists. List dispatching is very similar to the [Cull Pattern] component, with the exception that both lists are provided as outputs.</p>                                                                                                                    | ![IMAGE](../../.gitbook/assets/SLDispatch.png) |
| S.L.Ins      | <p>Insert Items<br>Insert a collection of items into a list.</p>                                                                                                                                                                                                                                                        | ![IMAGE](../../.gitbook/assets/SLIns.png)      |
| S.L.Item     | <p>List Item<br>Retrieve a specific item from a list.</p>                                                                                                                                                                                                                                                               | ![IMAGE](../../.gitbook/assets/SLItem.png)     |
| S.L.Lng      | <p>List Length<br>Measure the length of a list. Elements in a list are identified by their index. The first element is stored at index zero, the second element is stored at index one and so on and so forth. The highest possible index in a list equals the length of the list minus one.</p>                        | ![IMAGE](../../.gitbook/assets/SLLng.png)      |
| S.L.Long     | <p>Longest List<br>Grow a collection of lists to the longest length amongst them.</p>                                                                                                                                                                                                                                   | ![IMAGE](../../.gitbook/assets/SLLong.png)     |
| S.L.Split    | <p>Split List<br>Split a list into separate parts.</p>                                                                                                                                                                                                                                                                  | ![IMAGE](../../.gitbook/assets/SLSplit.png)    |
| S.L.Replace  | <p>Replace Items<br>Replace certain items in a list.</p>                                                                                                                                                                                                                                                                | ![IMAGE](../../.gitbook/assets/SLReplace.png)  |
| S.L.Rev      | <p>Reverse List<br>Reverse the order of a list. The new index of each element will be N-i where N is the highest index in the list and i is the old index of the element.</p>                                                                                                                                           | ![IMAGE](../../.gitbook/assets/SLRev.png)      |
| S.L.Shift    | <p>Shift List<br>Offset all items in a list. Items in the list are offset (moved) towards the end of the list if the shift offset is positive. If Wrap equals True, then items that fall off the ends are re-appended.</p>                                                                                              | ![IMAGE](../../.gitbook/assets/SLShift.png)    |
| S.L.Short    | <p>Shortest List<br>Shrink a collection of lists to the shortest length amongst them.</p>                                                                                                                                                                                                                               | ![IMAGE](../../.gitbook/assets/SLShort.png)    |
| S.L.Sift     | <p>Sift Pattern<br>Sift elements in a list using a repeating index pattern.</p>                                                                                                                                                                                                                                         | ![IMAGE](../../.gitbook/assets/SLSift.png)     |
| S.L.Sort     | <p>Sort List<br>Sort a list of numeric keys. In order for something to be sorted, it must first be comparable. Most types of data are not comparable, Numbers and Strings being basically the sole exceptions. If you want to sort other types of data, such as curves, you’ll need to create a list of keys first.</p> | ![IMAGE](../../.gitbook/assets/SLSort.png)     |
| S.L.Weave    | <p>Weave<br>Weave a set of input data using a custom pattern. The pattern is specified as a list of index values (integers) that define the order in which input data is collected.</p>                                                                                                                                 | ![IMAGE](../../.gitbook/assets/SLWeave.png)    |

\####Sets

|            |                                                                                                                                                                                                                                                                                                                                                              |                                              |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------- |
| S.S.Culli  | <p>Cull Index<br>Cull (remove) indexed elements from a list.</p>                                                                                                                                                                                                                                                                                             | ![IMAGE](../../.gitbook/assets/SSCulli.png)  |
| S.S.Cull   | <p>Cull Pattern<br>Cull (remove) elements in a list using a repeating bit mask. The bit mask is defined as a list of Boolean values. The bit mask is repeated until all elements in the data list have been evaluated.</p>                                                                                                                                   | ![IMAGE](../../.gitbook/assets/SSCull.png)   |
| S.S.Dup    | <p>Duplicate Data<br>Duplicate data a predefined number of times. Data can be duplicated in two ways, either copies of the list are appended at the end until the number of copies has been reached, or each item is duplicated a number of times before moving on to the next item.</p>                                                                     | ![IMAGE](../../.gitbook/assets/SSDup.png)    |
| S.S.Jitter | <p>Jitter<br>Randomly shuffles a list of values. The input list is reordered based on random noise. Jittering is a good way to get a random set with a good distribution. The jitter parameter sets radius of the random noise. If jitter equals 0.5, then each item is allowed to reposition itself randomly to within half the span of the entire set.</p> | ![IMAGE](../../.gitbook/assets/SSJitter.png) |
| S.S.Random | <p>Random<br>Generate a list of pseudo random numbers. The number sequence is unique but stable for each seed value. If you do not like a random distribution, try different seed values.</p>                                                                                                                                                                | ![IMAGE](../../.gitbook/assets/SSRandom.png) |
| S.S.Range  | <p>Range<br>Create a range of numbers. The numbers are spaced equally inside a numeric domain. Use this component if you need to create numbers between extremes. If you need control over the interval between successive numbers, you should be using the [Series] component.</p>                                                                          | ![IMAGE](../../.gitbook/assets/SSRange.png)  |
| S.S.Repeat | <p>Repeat Data<br>Repeat a pattern until it reaches a certain length.</p>                                                                                                                                                                                                                                                                                    | ![IMAGE](../../.gitbook/assets/SSRepeat.png) |
| S.S.Series | <p>Series<br>Create a series of numbers. The numbers are spaced according to the {Step} value. If you need to distribute numbers inside a fixed numeric range, consider using the [Range] component instead.</p>                                                                                                                                             | ![IMAGE](../../.gitbook/assets/SSSeries.png) |

\####Tree

|               |                                                                                                                                                                                                                                                                                                                                                                           |                                                 |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------- |
| S.T.Explode   | <p>Explode Tree<br>Extract all the branches from a tree.</p>                                                                                                                                                                                                                                                                                                              | ![IMAGE](../../.gitbook/assets/STExplode.png)   |
| S.T.Flatten   | <p>Flatten Tree<br>Flatten a data tree by removing all branching information.</p>                                                                                                                                                                                                                                                                                         | ![IMAGE](../../.gitbook/assets/STFlatten.png)   |
| S.T.Flip      | <p>Flip Matrix<br>Flip a matrix–like data tree by swapping rows and columns.</p>                                                                                                                                                                                                                                                                                          | ![IMAGE](../../.gitbook/assets/STFlip.png)      |
| S.T.Graft     | <p>Graft Tree<br>Typically, data items are stored in branches at specific index values (0 for the first item, 1 for the second item, and so on and so forth) and branches are stored in trees at specific branch paths, for example: {0;1}, which indicates the second sub-branch of the first main branch. Grafting creates a new branch for every single data item.</p> | ![IMAGE](../../.gitbook/assets/STGraft.png)     |
| S.T.Merge     | <p>Merge<br>Merge a bunch of data streams.</p>                                                                                                                                                                                                                                                                                                                            | ![IMAGE](../../.gitbook/assets/STMerge.png)     |
| S.T.Path      | <p>Path Mapper<br>Perform lexical operations on data trees. Lexical operations are logical mappings between data paths and indices which are defined by textual (lexical) masks and patterns.</p>                                                                                                                                                                         | ![IMAGE](../../.gitbook/assets/STPath.png)      |
| S.T.Prune     | <p>Prune Tree<br>Removes all branches from a Tree that carry a special number of Data items. You can supply both a lower and an upper limit for branch pruning.</p>                                                                                                                                                                                                       | ![IMAGE](../../.gitbook/assets/STPrune.png)     |
| S.T.Simplify  | <p>Simplify Tree<br>Simplify a tree by removing the overlap shared amongst all branches.</p>                                                                                                                                                                                                                                                                              | ![IMAGE](../../.gitbook/assets/STSimplify.png)  |
| S.T.TStat     | <p>Tree Statistics<br>Get some statistics regarding a data tree.</p>                                                                                                                                                                                                                                                                                                      | ![IMAGE](../../.gitbook/assets/STTStat.png)     |
| S.T.Unflatten | <p>Unflatten Tree<br>Unflatten a data tree by moving items back into branches.</p>                                                                                                                                                                                                                                                                                        | ![IMAGE](../../.gitbook/assets/STUnflatten.png) |

### Vector

\####Grid

|             |                                                       |                                               |
| ----------- | ----------------------------------------------------- | --------------------------------------------- |
| V.G.HexGrid | <p>Hexagonal<br>2D grid with hexagonal cells.</p>     | ![IMAGE](../../.gitbook/assets/VGHexGrid.png) |
| V.G.RecGrid | <p>Rectangular<br>2D grid with rectangular cells.</p> | ![IMAGE](../../.gitbook/assets/VGRecGrid.png) |
| V.G.SqGrid  | <p>Square<br>2D grid with square cells</p>            | ![IMAGE](../../.gitbook/assets/VGSqGrid.png)  |

\####Point

|            |                                                                              |                                              |
| ---------- | ---------------------------------------------------------------------------- | -------------------------------------------- |
| V.P.Pt     | <p>Construct Point<br>Construct a point from {xyz} coordinates.</p>          | ![IMAGE](../../.gitbook/assets/VPPt.png)     |
| V.P.pDecon | <p>Deconstruct<br>Deconstruct a point into its component parts.</p>          | ![IMAGE](../../.gitbook/assets/VPpDecon.png) |
| V.P.Dist   | <p>Distance<br>Compute Euclidean distance between two point coordinates.</p> | ![IMAGE](../../.gitbook/assets/VPDist.png)   |

\####Vector

|            |                                                              |                                              |
| ---------- | ------------------------------------------------------------ | -------------------------------------------- |
| V.V.X      | <p>Unit X<br>Unit vector parallel to the world {x} axis.</p> | ![IMAGE](../../.gitbook/assets/VVX.png)      |
| V.V.Y      | <p>Unit Y<br>Unit vector parallel to the world {y} axis.</p> | ![IMAGE](../../.gitbook/assets/VVY.png)      |
| V.V.Vec2Pt | <p>Vector 2Pt<br>Create a vector between two points.</p>     | ![IMAGE](../../.gitbook/assets/VVVec2Pt.png) |

### Curve

\####Analysis

|        |                                                                                 |                                          |
| ------ | ------------------------------------------------------------------------------- | ---------------------------------------- |
| C.A.CP | <p>Control Points<br>Extract the nurbs control points and knots of a curve.</p> | ![IMAGE](../../.gitbook/assets/CACP.png) |

\####Division

|            |                                                                   |                                              |
| ---------- | ----------------------------------------------------------------- | -------------------------------------------- |
| C.D.Divide | <p>Divide Curve<br>Divide a curve into equal length segments.</p> | ![IMAGE](../../.gitbook/assets/CDDivide.png) |

\####Primitive

|             |                                                                                      |                                               |
| ----------- | ------------------------------------------------------------------------------------ | --------------------------------------------- |
| C.P.Cir     | <p>Circle<br>Create a circle defined by base plane and radius.</p>                   | ![IMAGE](../../.gitbook/assets/CPCir.png)     |
| C.P.Cir3Pt  | <p>Circle 3Pt<br>Create a circle defined by three points.</p>                        | ![IMAGE](../../.gitbook/assets/CPCir3Pt.png)  |
| C.P.CirCNR  | <p>Circle CNR<br>Create a circle defined by center, normal and radius.</p>           | ![IMAGE](../../.gitbook/assets/CPCirCNR.png)  |
| C.P.Line    | <p>Line SDL<br>Create a line segment defined by start point, tangent and length.</p> | ![IMAGE](../../.gitbook/assets/CPLine.png)    |
| C.P.Polygon | <p>Polygon<br>Create a polygon with optional round edges.</p>                        | ![IMAGE](../../.gitbook/assets/CPPolygon.png) |

\####Spline

|             |                                                                                                            |                                               |
| ----------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------- |
| C.S.IntCrv  | <p>Interpolate<br>Create an interpolated curve through a set of points.</p>                                | ![IMAGE](../../.gitbook/assets/CSIntCrv.png)  |
| C.S.KinkCrv | <p>Kinky Curve<br>Construct an interpolated curve through a set of points with a kink angle threshold.</p> | ![IMAGE](../../.gitbook/assets/CSKinkCrv.png) |
| C.S.Nurbs   | <p>Nurbs Curve<br>Construct a nurbs curve from control points.</p>                                         | ![IMAGE](../../.gitbook/assets/CSNurbs.png)   |
| C.S.PLine   | <p>PolyLine<br>Create a polyline connecting a number of points.</p>                                        |                                               |

\####Util

|             |                                                            |                                               |
| ----------- | ---------------------------------------------------------- | --------------------------------------------- |
| C.U.Explode | <p>Explode<br>Explode a curve into smaller segments.</p>   | ![IMAGE](../../.gitbook/assets/CUExplode.png) |
| \<C.U.Join  | <p>Join Curves<br>Join as many curves as possible.</p>     | ![IMAGE](../../.gitbook/assets/CUJoin.png)    |
| C.U.Offset  | <p>Offset<br>Offset a curve with a specified distance.</p> | ![IMAGE](../../.gitbook/assets/CUOffset.png)  |

### Surface

\####Analysis

|            |                                                                           |                                              |
| ---------- | ------------------------------------------------------------------------- | -------------------------------------------- |
| S.A.DeBrep | <p>Deconstruct Brep<br>Deconstruct a brep into its constituent parts.</p> | ![IMAGE](../../.gitbook/assets/SADeBrep.png) |

\####Freeform

|              |                                                                                               |                                                |
| ------------ | --------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| S.F.Boundary | <p>Boundary Surfaces<br>Create planar surfaces from a collection of boundary edge curves.</p> | ![IMAGE](../../.gitbook/assets/SFBoundary.png) |
| S.F.Extr     | <p>Extrude<br>Extrude curves and surfaces along a vector.</p>                                 | ![IMAGE](../../.gitbook/assets/SFExtr.png)     |
| S.F.ExtrPt   | <p>Extrude Point<br>Extrude curves and surfaces to a point.</p>                               | ![IMAGE](../../.gitbook/assets/SFExtrPt.png)   |
| S.F.Loft     | <p>Loft<br>Create a lofted surface through a set of section curves.</p>                       | ![IMAGE](../../.gitbook/assets/SFLoft.png)     |
| S.F.RevSrf   | <p>Revolution<br>Create a surface of revolution.</p>                                          | ![IMAGE](../../.gitbook/assets/SFRevSrf.png)   |
| S.F.Swp2     | <p>Sweep2<br>Create a sweep surface with two rail curves.</p>                                 | ![IMAGE](../../.gitbook/assets/SFSwp2.png)     |

\####Primitive

|          |                                                                |                                            |
| -------- | -------------------------------------------------------------- | ------------------------------------------ |
| S.P.BBox | <p>Bounding Box<br>Solve oriented geometry bounding boxes.</p> | ![IMAGE](../../.gitbook/assets/SPBBox.png) |

\####Util

|             |                                                                       |                                               |
| ----------- | --------------------------------------------------------------------- | --------------------------------------------- |
| S.U.SDivide | <p>Divide Surface<br>Generate a grid of {uv} points on a surface.</p> | ![IMAGE](../../.gitbook/assets/SUSDivide.png) |
| S.U.SubSrf  | <p>Isotrim<br>Extract an isoparametric subset of a surface.</p>       | ![IMAGE](../../.gitbook/assets/SUSubSrf.png)  |

### Mesh

\####Triangulation

|             |                                                                      |                                               |
| ----------- | -------------------------------------------------------------------- | --------------------------------------------- |
| M.T.Voronoi | <p>Voronoi<br>Planar voronoi diagram for a collection of points.</p> | ![IMAGE](../../.gitbook/assets/MTVoronoi.png) |

### Transform

\####Affine

|            |                                                                                 |                                              |
| ---------- | ------------------------------------------------------------------------------- | -------------------------------------------- |
| T.A.RecMap | <p>Rectangle Mapping<br>Transform geometry from one rectangle into another.</p> | ![IMAGE](../../.gitbook/assets/TARecMap.png) |

\####Array

|               |                                                           |                                                 |
| ------------- | --------------------------------------------------------- | ----------------------------------------------- |
| T.A.ArrLinear | <p>Linear Array<br>Create a linear array of geometry.</p> | ![IMAGE](../../.gitbook/assets/TAArrLinear.png) |

\####Morph

|           |                                                                |                                             |
| --------- | -------------------------------------------------------------- | ------------------------------------------- |
| T.M.Morph | <p>Box Morph<br>Morph an object into a twisted box.</p>        | ![IMAGE](../../.gitbook/assets/TMMorph.png) |
| T.M.SBox  | <p>Surface Box<br>Create a twisted box on a surface patch.</p> | ![IMAGE](../../.gitbook/assets/TMSBox.png)  |

### Display

\####Color

|         |                                                                          |                                           |
| ------- | ------------------------------------------------------------------------ | ----------------------------------------- |
| D.C.HSL | <p>Colour HSL<br>Create a colour from floating point {HSL} channels.</p> | ![IMAGE](../../.gitbook/assets/DCHSL.png) |

\####Dimensions

|           |                                                                                                                                                                                                                       |                                             |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| D.D.Tag   | <p>Text tags<br>A text tag component allows you to draw little Strings in the viewport as feedback items. Text and location are specified as input parameters. When text tags are baked they turn into Text Dots.</p> | ![IMAGE](../../.gitbook/assets/DDTag.png)   |
| D.D.Tag3D | <p>Text Tag 3D<br>Represents a list of 3D text tags in a Rhino viewport</p>                                                                                                                                           | ![IMAGE](../../.gitbook/assets/DDTag3D.png) |

\####Preview

|             |                                                                   |                                               |
| ----------- | ----------------------------------------------------------------- | --------------------------------------------- |
| D.P.Preview | <p>Custom Preview<br>Allows for customized geometry previews.</p> | ![IMAGE](../../.gitbook/assets/DPPreview.png) |

\####Vector

|            |                                                              |                                              |
| ---------- | ------------------------------------------------------------ | -------------------------------------------- |
| D.V.Points | <p>Point List<br>Displays details about lists of points.</p> | ![IMAGE](../../.gitbook/assets/DVPoints.png) |
