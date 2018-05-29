# Data-Mining-and-Business-Intelligence

## Identification of Attributes

The type of an attribute is determined by the set of possible values

1. Nominal Attributes
	
	a. Nominal means “relating to names.”

	b. The values of a nominal attribute are symbols or names of things

	c. Each value represents some kind of category, code, or state

	d. Nominal attributes are also referred to as categorical

	e. Example of a nominal attribute is occupation, with the values teacher, dentist, programmer, farmer, and so on.

2. Binary Attributes

	a. A binary attribute is a nominal attribute with only two categories or states: 0 or 1

	b. Where 0 typically means that the attribute is absent, and 1 means that it is present

	c. Given the attribute smoker describing a patient object, 1 indicates that the patient smokes, while 0 indicates that the patient does not

3. Ordinal Attributes
	
	a. Attribute with possible values that have a meaningful order or ranking among them

	b. Example: grade (e.g., A+, A, A−, B+, and so on) and professional rank.

	c. Ordinal attributes may also be obtained from the discretization of numeric quantities by splitting the value range into a finite number of ordered categories

4. Numeric Attributes
	
	a. A numeric attribute is quantitative; that is, it is a measurable quantity, represented in integer or real values

	b. Numeric attributes can be interval-scaled or ratio-scaled

	c. Interval-scaled attributes are measured on a scale of equal-size units. The values of interval-scaled attributes have order and can be positive, 0, or negative

	d. A ratio-scaled attribute is a numeric attribute with an inherent zero-point. That is, if a measurement is ratio-scaled, we can speak of a value as being a multiple (or ratio) of another value. 

## Similarity and Dissimilarity Measures

1. Similarity and dissimilarity are related. Similarity and dissimilarity measures are referred to as measures of proximity

2. A similarity measure for two objects, i and j, will be 0 if the objects are similar. A value of 1 indicates complete disimilarity, that is, the objects are not at all identical.

3. A dissimilarity measure works the opposite way.

4. sim(i, j) = 1 − d(i, j)

5. The measures of similarity and dissimilarity vary for different types of attributes.

6. For Nominal Attributes
	
	a. The dissimilarity between two objects i and j can be computed based on the ratio of mismatches: d(i, j) = (p − m)/p

	b. Where m is the number of matches (i.e., the number of attributes for which i and j are in the same state), and p is the total number of attributes describing the objects.

7. For Binary Attributes 
	
	a. Binary attributes are nominal attributes with only two possible states (such as 1 and 0 or true and false)

## Major Issues in Data Mining
### Mining Methodology
	1. Mining various and new kinds of knowledge: Due to the diversity of applications, new mining tasks continue to emerge, making data mining a dynamic and fast-growing field

	2. Mining knowledge in multidimensional space: n many cases, data can be aggregated or viewed as a multidimensional data cube. Mining knowledge in cube space can substantially enhance the power and flexibility of data mining. 

	3. Data mining

	4. Handling uncertainty, noise, or incompleteness of data

### User Interaction
	
	1. Interactive mining: Build flexible user interfaces and an exploratory mining environment, facilitating the user’s interaction with the system

	2. Incorporation of background knowledge

	3. Ad hoc data mining and data mining query languages

	4. Presentation and visualization of data mining results

### Efficiency and Scalability

	1. Efficiency and scalability of data mining algorithms

	2. Parallel, distributed, and incremental mining algorithms

### Diversity of Database Types

	1. Handling complex types of data

	2. Mining dynamic, networked, and global data repositories

### Data Mining and Society
	
	1. Social impacts of data mining: The improper disclosure or use of data and the potential violation of individual privacy and data protection rights are areas of concern that need to be addressed.

	2. Privacy-preserving data mining: The philosophy is to observe data sensitivity and preserve people’s privacy while performing successful data mining.

	3. Invisible data mining: For example, when purchasing items online, users may be unaware that the store is likely collecting data on the buying patterns of its customers, which may be used to recommend other items for purchase in the future. 

## Data Visualization techniques
Data visualization is presenting the data in a graphical or pictorial format. Data visualization aims to communicate data clearly and effectively through graphical representation. Patterns in the data can be marked very easily using the data visualization techniques. Some of the data visualization techniques are as follows:

### Pixel-oriented visualization techniques

1. A simple way to visualize the value of a dimension is to use a pixel where the color of the pixel reflects the dimension’s value.

2. For a data set of M dimensions, pixel-oriented techniques create M windows on the screen, one for each dimension. 

3. The M dimension values of a record are mapped to M pixels at the corresponding positions in the windows. The colors of the pixels reflect the corresponding values. 

4. Inside  a  window,  the  data  values  are  arranged  in  some  global  order  shared  by  all windows. The global order may be obtained by sorting all data records in a way that’s meaningful for the task at hand

5. A drawback of pixel-oriented visualization techniques is that they cannot help us much in understanding the distribution of data in a multidimensional space

### Geometric projection visualization techniques

1. This help users find interesting projections of multidimensional data sets

2. A scatter plot displays 2-D data points using Cartesian coordinates. A third dimension can be added using different colors or shape

3. For data sets with more than four dimensions, scatter plots are usually ineffective



