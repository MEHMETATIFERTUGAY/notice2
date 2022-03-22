# int main (){
int sum=0;
int read=0;
int num=0;
while(true){
    cout<<"please enter number "<<endl;
    cin >> read;
    if(read == -1)
        break;
        sum+=read;
        num++;


}
cout <<"sum: " << sum << endl;
cout << "num: " << num << endl;
cout << "average: " << sum/num << endl;
}
