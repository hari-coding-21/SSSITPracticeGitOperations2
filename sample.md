
story - 2

class preorder(BinaryNode node)
{
    if(node == null)
    {
        return;
    }
    Sysout(node.value+" ");
    preorder(node.left);
    preorder(node.right);
}
