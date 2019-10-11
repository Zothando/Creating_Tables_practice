# Creating_Tables_practice
# SQL Language

CREATE TABLE Georeferenced_Records(
	QDS varchar(6),
	Locality_description varchar,
	Coordinates_Lat_Long varchar,
	Georeference_status varchar,
);
INSERT INTO Georeferenced_Records (QDS, Locality_description, Coordinates_Lat_Long, Georeference_status)
VALUES ("QDS", "locality", " ", " ")
VALUES* FROM RDE25_For_Georeferencing
