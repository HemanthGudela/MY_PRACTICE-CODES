# MY_PRACTICE-CODES
Here i keep the codes which i practice 
1)REVERSE,SIZE,PRINT,SORT IN ASC ORDER,DESC ORDER.
void add_to_vector(vector<int> &A,int x)
{
	A.push_back(x);
}
void sort_vector_asc(vector<int> &A)
{
	sort(A.begin(),A.end());
}
void reverse_vector(vector<int> &A)
{
	reverse(A.begin(),A.end());
}
int size_of_vector(vector<int> &A)
{
	return(A.size());//Your code here
}
void sort_vector_desc(vector<int> &A)
{
	sort(A.begin(),A.end(),greater<int>());//gretaer<data type>
}
void print_vector(vector<int> &A)
{
	for(int i=0;i<A.size();i++)
	cout<<A[i]<<" ";
}

