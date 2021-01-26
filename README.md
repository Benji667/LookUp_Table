# LookUp Table API

The Look up tabel (LUT) consists on a LabVIEW variant, that stores the data. We use the capacity of the LabVIEW Variant to store additional information in the form of Variant Attributes. Variant attributes are key-value pairs of data that can contain any sort of information. LabVIEW uses the red-black tree implementation to store Variant Attributes wich allows efficient and fast access to the data. 

The LUT Object encapsulates the Variant in a Data Value By Reference. The use of the In Place Element Structure to get and operate on data, allows us to access data in place to reduce memory footprint.



