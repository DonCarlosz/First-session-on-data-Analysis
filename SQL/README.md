```sql 
   CREATE TABLE `intern_information` (
  `Name` varchar(255) DEFAULT NULL,
  `Location` varchar(255) DEFAULT NULL,
  `Gender` varchar(255) DEFAULT NULL,
  `Age` int(11) DEFAULT NULL,
  `date_of_birth` date DEFAULT NULL


  INSERT INTO `intern_information` (`Name`, `Location`, `Gender`, `Age`, `date_of_birth`) VALUES
  ('Johnson', 'Benin', 'Male', 35, '1999-12-30'),
  ('Jennifer', 'Abuja', 'Female', 30, '2002-02-01'),
  ('Destiny', 'Warri', 'Male', 37, '2002-02-01'),
  ('Wisdom', 'Lagos', 'Male', 21, '2002-02-01');
  COMMIT;
)

```

```sql
   CREATE TABLE `corpers_details` (
  `id` int(11) NOT NULL,
  `first_name` varchar(50) NOT NULL,
  `last_name` varchar(50) NOT NULL,
  `email` varchar(100) NOT NULL,
  `phone` int(20) NOT NULL,
  `address` varchar(100) NOT NULL,
  `city` varchar(50) NOT NULL,
  `state` varchar(50) NOT NULL,
  `zip_code` date NOT NULL,
  `gender` varchar(10) NOT NULL,
  `country` varchar(50) NOT NULL,
  `date_of_birth` int(20) NOT NULL,
  `weight_KG` decimal(10,0) NOT NULL,
  `height_CM` decimal(10,0) NOT NULL,
  `status` varchar(50) NOT NULL



  INSERT INTO `corpers_details` (`id`, `first_name`, `last_name`, `email`, `phone`, `address`, `city`, `state`, `zip_code`, `gender`, `country`, `date_of_birth`, 
 `weight_KG`, `height_CM`, `status`) VALUES
 (1, 'Isaiah', 'Matthew', 'isaiah@gmail.com', 1234567890, '123 Main St', 'Uromi', 'Edo state', '0000-00-00', 'Male', 'Nigeria', 1990, 80, 180, 'Active'),
 (2, 'Levi', 'Ackerman', 'levi@gmail.com', 2147483647, '123 Main St', 'Warri', 'Delta State', '2002-10-01', 'Male', 'Nigeria', 1990, 60, 181, 'Active'),
 (3, 'John', 'Matthew', 'john@gmail.com', 2147483647, '123 Main St', 'Abraka', 'Delta State', '2002-10-01', 'Male', 'Nigeria', 1995, 70, 161, 'Inactive'),
 (4, 'Destiny', 'Wisdom', 'destiny@gmail.com', 2147483647, '123 Main St', 'Benin', 'Edo state', '0000-00-00', 'Male', 'Nigeria', 2000, 100, 151, 'Active'),
 (5, 'Timothy', 'Okuchuku', 'timothy@gmail.com', 2147483647, '123 Main St', 'Auchi', 'Edo state', '0000-00-00', 'Male', 'Nigeria', 2001, 94, 171, 'Inactive'),
 (6, 'Emmanuel', 'Derek', 'derek@gmail.com', 2147483647, '123 Main St', 'Ekpoma', 'Edo state', '0000-00-00', 'Male', 'Nigeria', 2003, 90, 161, 'Active'),
 (2, 'Blessing', 'Akhuemokhan', 'blessing@gmail.com', 2147483647, '123 Main St', 'Ughelli', 'Delta State', '2002-10-01', 'Female', 'Nigeria', 2003, 80, 177, 
 'Active'),
 (7, 'Success', 'Rich', 'success@gmail.com', 2147483647, '123 Main St', 'Lekki', 'Lagos State', '0000-00-00', 'Female', 'Nigeria', 2004, 91, 191, 'Inactive'),
 (8, 'Terry', 'Garnacho', 'terry@gmail.com', 2147483647, '123 Main St', 'Ikeja', 'Lagos State', '0000-00-00', 'Male', 'Nigeria', 1995, 85, 120, 'Active'),
 (9, 'Kevin', 'Foden', 'kevin@gmail.com', 2147483647, '123 Main St', 'Asaba', 'Delta State', '2002-10-01', 'Male', 'Nigeria', 1899, 81, 140, 'Active'),
 (10, 'Caleb', 'Eben', 'caleb@gmail.com', 2147483647, '123 Main St', 'Uromi', 'Edo state', '0000-00-00', 'Male', 'Nigeria', 1999, 75, 200, 'Inactive');
 COMMIT;
)

```
