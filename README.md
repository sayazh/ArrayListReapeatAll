# ArrayListReapeatAll
ArrayListReapeatAll
public static void main(String[] args)
		{
			ArrayList<Boolean> list=new ArrayList<Boolean>();
			list.add(true);
			list.add(false);
			list.add(false);
			list.add(false);
			repeatAL(list);
			
		}
		//create your method below
		public static void repeatAL(ArrayList<Boolean> bool) {
		
			
	     	bool.addAll(bool);
			
			System.out.println(bool);
			
	}
}
