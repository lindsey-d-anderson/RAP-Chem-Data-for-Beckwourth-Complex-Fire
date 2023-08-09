# RAP Chem Data for the Beckwourth Complex Fire
# Last updated by Lindsey Anderson on August 9, 2023

Data files can be downloaded here and viewed using tools such as Panopoly (https://www.giss.nasa.gov/tools/panoply/) or ncview (https://cirrus.ucsd.edu/~pierce/software/ncview/quick_intro.html). 

Variables are described bellow:
Min latitude, max latitude: 36.3, 43.4
Min longitude, max longitude: -125.1, -115.9

Variable "ASYMPAR106"
float ASYMPAR106(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "assymetry parameter for 1.06um";
  :units = "?";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "ASYMPAR3"
float ASYMPAR3(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "assymetry parameter for .3um";
  :units = "?";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "ASYMPAR55"
float ASYMPAR55(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "assymetry parameter for .55um";
  :units = "?";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "BSCOF106"
float BSCOF106(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "Scatter coefficients for 1.06um";
  :units = "km^-1";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "BSCOF3"
float BSCOF3(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "Scatter coefficients for .3um";
  :units = "km^-1";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "BSCOF5"
float BSCOF5(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "Scatter coefficients for .5um";
  :units = "km^-1";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "co"
float co(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "CO mixing ratio";
  :units = "ppmv";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "ebu_co"
float ebu_co(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "biomass burning emiss";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "ebu_in_c10h16"
float ebu_in_c10h16(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :coordinates = "longitude latitude";
  :description = "EMISSIONS";
  :grid_mapping = "latitude_longitude";
  :stagger = "";
  :units = "mol km^-2 hr^-1";

Variable "ebu_in_c2h4"
float ebu_in_c2h4(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_ch3cho"
float ebu_in_ch3cho(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_co"
float ebu_in_co(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_eci"
float ebu_in_eci(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_ecj"
float ebu_in_ecj(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_hcho"
float ebu_in_hcho(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_isop"
float ebu_in_isop(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_ivoc"
float ebu_in_ivoc(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_mgly"
float ebu_in_mgly(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_nh3"
float ebu_in_nh3(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_no"
float ebu_in_no(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_no2"
float ebu_in_no2(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_no3i"
float ebu_in_no3i(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_no3j"
float ebu_in_no3j(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_ole"
float ebu_in_ole(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :coordinates = "longitude latitude";
  :description = "EMISSIONS";
  :grid_mapping = "latitude_longitude";
  :stagger = "";
  :units = "mol km^-2 hr^-1";

Variable "ebu_in_orgi"
float ebu_in_orgi(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_orgj"
float ebu_in_orgj(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_par"
double ebu_in_par(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :coordinates = "longitude latitude";
  :description = "EMISSIONS";
  :grid_mapping = "latitude_longitude";
  :stagger = "";
  :units = "mol km^-2 hr^-1";

Variable "ebu_in_pm25i"
float ebu_in_pm25i(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_pm25j"
float ebu_in_pm25j(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_so2"
float ebu_in_so2(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_so4i"
float ebu_in_so4i(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_so4j"
float ebu_in_so4j(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "ug m^-2 s^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_in_soaalk"
float ebu_in_soaalk(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :coordinates = "longitude latitude";
  :description = "EMISSIONS";
  :grid_mapping = "latitude_longitude";
  :stagger = "";
  :units = "mol km^-2 hr^-1";

Variable "ebu_in_tol"
float ebu_in_tol(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "EMISSIONS";
  :units = "mol km^-2 hr^-1";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "ebu_orgi"
float ebu_orgi(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "biomass burning emiss";
  :units = "ug/m2/s";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "ebu_orgj"
float ebu_orgj(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "biomass burning emiss";
  :units = "ug/m2/s";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "EXTCOF106"
float EXTCOF106(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "Extinction coefficients for 1.06um";
  :units = "km^-1";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "EXTCOF3"
float EXTCOF3(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "Extinction coefficients for .3um";
  :units = "km^-1";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "EXTCOF55"
float EXTCOF55(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "Extinction coefficients for .55um";
  :units = "km^-1";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "hcho"
float hcho(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "HCHO mixing ratio";
  :units = "ppmv";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "MEAN_FRP"
float MEAN_FRP(Time=1, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XY ";
  :description = "bbem2 mean FRP";
  :units = "?";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "MEAN_FSIZE"
float MEAN_FSIZE(Time=1, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XY ";
  :description = "bbem2 mean Size";
  :units = "?";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "no"
float no(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "NO mixing ratio";
  :units = "ppmv";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "no2"
float no2(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "NO2 mixing ratio";
  :units = "ppmv";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "o3"
float o3(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "O3 mixing ratio";
  :units = "ppmv";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "P"
float P(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "perturbation pressure";
  :units = "Pa";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "PB"
float PB(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "BASE STATE PRESSURE";
  :units = "Pa";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "PH"
float PH(Time=1, bottom_top_stag=51, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "perturbation geopotential";
  :units = "m2 s-2";
  :stagger = "Z";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "PHB"
float PHB(Time=1, bottom_top_stag=51, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "base-state geopotential";
  :units = "m2 s-2";
  :stagger = "Z";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "PM2_5_DRY"
float PM2_5_DRY(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "pm2.5 aerosol dry mass";
  :units = "ug m^-3";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "QVAPOR"
float QVAPOR(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "Water vapor mixing ratio";
  :units = "kg kg-1";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "STD_FRP"
float STD_FRP(Time=1, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XY ";
  :description = "bbem2 FRP standard deviation";
  :units = "?";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "STD_FSIZE"
float STD_FSIZE(Time=1, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XY ";
  :description = "bbem2 Size standard deviation";
  :units = "?";
  :stagger = "";
  :coordinates = "longitude latitude";
  :grid_mapping = "latitude_longitude";

Variable "T"
float T(Time=1, bottom_top=50, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XYZ";
  :description = "perturbation potential temperature (theta-t0)";
  :units = "K";
  :stagger = "";
  :coordinates = "XLONG XLAT XTIME";
  :cell_methods = "Time: mean";

Variable "XLAT"
float XLAT(Time=1, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XY ";
  :description = "LATITUDE, SOUTH IS NEGATIVE";
  :units = "degree_north";
  :stagger = "";
  :coordinates = "XLONG XLAT";
  :cell_methods = "Time: mean";

Variable "XLONG"
float XLONG(Time=1, south_north=51, west_east=51);
  :FieldType = 104; // int
  :MemoryOrder = "XY ";
  :description = "LONGITUDE, WEST IS NEGATIVE";
  :units = "degree_east";
  :stagger = "";
  :coordinates = "XLONG XLAT";
  :cell_methods = "Time: mean";

Variable "XTIME"
float XTIME(Time=1);
  :FieldType = 104; // int
  :MemoryOrder = "0  ";
  :description = "minutes since 2021-07-07 06:00:00";
  :units = "minutes since 2021-07-07 06:00:00";
  :stagger = "";
  :cell_methods = "Time: mean";

Variable "z"
short z(bottom_top=50);
  :units = "";
  :long_name = "synthesized coordinate: only an index";
  :_CoordinateAxisType = "GeoZ";
  :_CoordinateAliasForDimension = "bottom_top";

Variable "z_stag"
short z_stag(bottom_top_stag=51);
  :units = "";
  :long_name = "synthesized coordinate: only an index";
  :_CoordinateAxisType = "GeoZ";
  :_CoordinateAliasForDimension = "bottom_top_stag";
