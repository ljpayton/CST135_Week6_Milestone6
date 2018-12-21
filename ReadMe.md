# Hutto & Payton Vending Machine 

The goal for Week 6:
Read Products from CSV File


## Things that need to be fixed:
- Gut the unnecessary  components 
-Create Search Box that reads from inventory.csv
-The pay button deducts from Inventory



## Additions for Week 6 versus prior Weeks 

CSV File ```bash 
inventory.csv
```
```java
//	=============Reading From String====================================	
		String fName = "../Milestone3/inventory.csv";
		File file = new File(fName);
		try {
			Scanner inputStream = new Scanner(file);
			inputStream.next();
			while(inputStream.hasNext()) {
				String data = inputStream.next();
//				String [] values = data.split(",");
				System.out.println(data);
			}
			inputStream.close();
		}catch (FileNotFoundException e) {
		e.printStackTrace();
	}
	}
//	=============Reading From String====================================
```

## Contributers
Lyric Payton & James Hutto

