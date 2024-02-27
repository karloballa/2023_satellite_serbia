# 2023_satellite_serbia
40K+ locations, 480K+ satellite images
~80x80 pixels, ~800x800 meters

input: [{
  bands: [
  "B01", "B02", "B03", "B04", "B05",
  "B06", "B07", "B08", "B8A", "B09",
  "B11", "B12", 
  "CLP", "CLM", "dataMask"
  ],
}],
output: {
  bands: 15,
  sampleType: SampleType.FLOAT32
}



