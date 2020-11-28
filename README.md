public static <string,double extends comparable <double>>map<string,double>
  sortbyvalues(final map<string,value>map){
  Comparator<string>valueComparator=new Comparator<string>(){
  public int compare(string k1,string k2){
  int compare=map.get(k1).compareTo(map.get(k2)
  if(compare==0)
  return 1;
  else
  return compare;
  }
  };
  map<string,double>sortedByvalues=new Treemap<string,double>(valuesComparator);
  sortByvalues.putAll(map);
  return sortedByvalues;
  }
  HPG=arr[0]
  printf("array of first element,%d,HPG)
  for(i=1;i<arr.length;i++)
                            {
                            if(HPG<arr[i])
  HPG=arr[i];
  }
  LPG=arr[0]
  printf("array of element,%d,LPG)
  for(i=1;i<arr.length;i++)
                            {
                            if(LPG>arr[i]
  LPG=arr[i];
  }
  result=HPG-LPG
  
